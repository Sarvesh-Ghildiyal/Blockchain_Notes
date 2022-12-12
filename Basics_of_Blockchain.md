>In Day2 we understood need for blockchain now, lets take a look  on the  Blockchain itself.

For basic terminologies of blockchain visit: https://objectcomputing.com/expertise/blockchain/glossary


## Decentralization
Decentralization is one of the signature properties of the blockchain. It is needed to remove control of a single entity. It also removes the single point of failure

>Decentralised network is slight different from Distributed network


In distributed networks many system are attached together to share resources and achieve a common goal but in decentralised one different systems are connected but not for the purpose of common goal but _to eliminate the single point_ and also no node is working on common goals instead are on their own, which gives us the concept of **consensus** for decision making in the blockchain network.


## Immutability
One of the awesome feature of block chain network is, it is immutable which means once the data is stored on the blockchain, changing or altering it is impossible. This creates a very secure system that is impossible to hack or alter the data in a malicious way.  
         
        As, Blockchain stores transactions in a unit of memory called blocks which has a specific memory size. These blocks are then chained together in a progressive order such that changing data even in one block will result in affecting all the blocks after it.


## Transparency
Blockchain offers complete transparency. Every transaction that is ever happened on the network is visible to anyone.  

This way you can trust the system more than the censored one as all the money flow can be explored by anyone. 

        This transparency feature gives  us the perfect solution for **Double spending** problem.


### Solution to DOUBLE SPENDING
So, whenever a transaction is made in the blockchain network a record of that transaction is sent to all the nodes present in the network and that transaction will furthere be stored in the _Memory pool_ of the node.

This tells us about two things:
1. Each node contains data of all the transaction ever made in the netwrok.
2. Having *single history of the transactions in the netwrok* prevent us from _double spending_ in the system.


### How a blockchain ledger is maintained

1. User generates a valid transaction, which contains _sender's address, reciever's address and the ammount_.

2. Now, this transaction is broadcasted to all nodes in the block chain netwrok.

        As every node in the network receives the transaction, it places that transaction into its memory pool or Mempool. The Mempool is a collection of all the bitcoin transactions that are in an unconfirmed state and are still considered active.



3. If the transaction is confirmed by the miner, a new block will be created in the blockchain and that data related to the respective transaction will be stored in the block.

        When a block is successfully created, those transactions are removed from the mempool, while the remainder of the pool is eligible to be included in the next block.


**NOTE**: A transaction is considered to be confirmed by the entire Bitcoin network when the network has achieved consensus to include the transaction’s block in the blockchain.



>Some of the text in this document is taken from dAppworld Block chain course.