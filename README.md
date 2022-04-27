# MerkleTree
Merkle tree is a data structure that allows for efficient and secure verification of content in a large body of data. This structure helps verify the consistency and content of the data. Merkle trees are used by both Bitcoin and Ethereum.
Let’s say we have 4 transactions Transaction A, Transaction B, Transaction C, Transaction D
Merkel Tree is built by recursively hashing transactions until we obtain a single root hash.
If we have an odd number of transactions, the last transaction is duplicated.
If any of the transaction is modified, the root hash changes and shows that one of the transaction has been modified. This is used in blockchain to verify that data isn’t modified in a block.
