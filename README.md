# Posist-Placement
Our application will consist of the following:

Our block and blockchain
A Node which will run on team members machines, listening for new blocks broadcast and also broadcasting new blocks and updating the chain.
An HTTP server and web interface for interacting with brew activities, the log and other data.

To start with we need to determine the essential elements of our block.

timestamp
index (optional)
data - whatever we wish to store in the block
referenceNode-refer to address of node.
childReferenceNode-refer to address of child node.
hash - (a hash of the timestamp,index,data and previous hash)
previous hash - the hash of the previous block

Our Brewchain contains the ability to create new blocks, add new blocks to our chain and also check the validity of a block.
The test code at the end adds two blocks and then outputs the chain to check that the blocks are successfully being created.
