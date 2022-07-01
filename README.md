DEXTER’S BLOCKCHAIN
# Project Scenario(Description):

Dexter owns a coffee shop. As his coffee shop is very famous, the logbooks are prone to change. He needs his transactions to be immutable and safe. Hence, he uses a block chain to keep a track of his transactions and the history of the transactions to be safe. The purpose of this project is to help Dexter implement the block chain in order for the transaction history to be immutable and many more.Security is also one of the most essential feature to be implemented correctly. For this very reason, we need to implement a consensus algorithm in the blockchain. 
More about it in the later part.

# A Glance on the emerging technology of Blockchain:
The block chain is basically a distributed database. It’s distributed. It’s open source, so anyone can change the underlying code, and they can see what’s going on. It’s truly peer to peer.
It uses state-of-the-art cryptography, so if we have a global, distributed database that can record the fact that we’ve done this transaction and also it could record any structured information, not just who paid whom but also who married whom or who owns what land, etc. In the case of the Internet of Things, we’re going to need a block chain-settlement system underneath. Banks won’t be able to settle trillions of real-time transactions between things. So, this is an extraordinary thing. An immutable, unhackable distributed database of digital assets. This is a platform for truth and it’s a platform for trust
# A Glance on the concept of Consensus Algorithms
We all know that block chain is a peer-to-peer network. It is essential for the network to reach for an agreement in the crucial aspects of the block chain. In order to do that, we have consensus algorithms which is an agreement between all the nodes in the network to agree upon the true state of the block chain.
It is also the main reason why block chains are so secure even in the absence of a central authority. These algorithms achieve reliability in the block chain network and establish trust between unknown peers in the distributed computing environment of block chain. It makes sure that every new block that is added to the block chain is the one and only true version of truth that is agreed upon by all the nodes in the block chain.

In this project, we implemented the consensus algorithm of the Proof of elapsed time(PoET).
# Proof of Elapsed Time(PoET)
Its a block chain network consensus mechanism  that prevents high resource utilization and high energy consumption and keeps the process more efficient by following a fair lottery system. The algorithm uses a randomly generated elapsed time to decide mining rights and block winners on a blockchain network. By running a trusted code within a secure environment, the PoET algorithm also enhances transparency by ensuring lottery results are verifiable by external participants.
# Execution
Step-1: Run the file consensus.py
Step-2: Select the required option according to the function you require. The image below is the menu.
![image](https://user-images.githubusercontent.com/86017986/176825744-a5016ba0-65db-481a-b8e7-7f88f2ebea9c.png)
For example, if we press 1, we are asked to enter the name of the participant and the account balance. In this way, we can store the participants and the currency they possess.

We press 2 when we want to create a transaction and validate it. We can also print the receipt as per their interest till the limit of the transactions is reached.

As we kept the limit of the transactions to the blocks to be 3, after three transactions, in order to create a new block,
 
we use the algorithm of Proof of Elapsed Time (PoET) in order to elect the leader of the present round of consensus. We get the leader of the consensus round printed and also the block which got created as in the image below.
 
![image](https://user-images.githubusercontent.com/86017986/176826197-da7addd6-212f-4a87-b007-dad04bd61f38.png)


We press 3 when we want to know the currency that each person in the network has.
We press 4 when we want to print the existing block chain We press 5 to exit the program.
# Functionalities
•	The program goes to sleep for the minimum wait time assigned randomly in order to know the leader of the round.

•	The algorithm is not resource-intensive like Proof of Work(PoW).

•	The algorithm gives the chance of creating a block to all the nodes in the system by fair lottery.


# Contributors
 
Himaja Sai Dama (2019A3PS0464H)
Lakkireddy Lakshmi Bhavitha (2019AAPS0222H) 
Yadala Sai Chaitanya (2019AAPS0296H)
