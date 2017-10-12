# My introduction to Blockchain

In the way that I began to walk to learn about blockchain, I decided to register and share some concepts to keep the knowledge and at the same time make it available for those who are interested in the subject.

I will start with an introduction to blockchain and I plan to continue with a series of articles that will allow us to go deeper into the subject.

## What is blockchain?

Blockchain is a distributed database that functions as an account book for recording transactions, hence the name Distributed Ledger Technology. Records grow continuously and have the characteristic of being immutable.

The information is stored in blocks that are linked to each other in an encrypted and chronological way. Using cryptographic keys and being distributed among many computers has advantages in terms of security against manipulation and fraud. A modification in one of the copies would be of no use, but it is necessary to make the change in all the copies because the base is open and public. In other words, everything is resolved by consensus of the parties being this and decentralization what allows to remove the middle man. Is this the end of intermediaries?

## How does a blockchain work?

According to its original design conceived by Satoshi Nakamoto (pseudonym), it is a peer-to-peer network composed of client and servers (miners, who verify and maintain the integrity of records and the ledger).
Client nodes request the servers to store transactions. Transactions are signed using a public key scheme guaranteeing their authenticity and at the same time ensuring the participation of the parties.

The servers are then responsible for entering the transaction in blocks in the ledger (mine), by solving cryptographic riddles, proving that resources have been committed for this purpose. This process is known as proof of work (PoW). This proof of work is easily verifiable, but its production is very expensive. There are other methods of mining that I will mention later.

Once the block and its PoW are generated, both are forwarded to the remaining servers, which will verify its validity. Accepted blocks are added to the ledger and the server that generated the update receives its reward for the work performed (usually in cryptocurrency).

As the same acceptance rules applies for all nodes, the network reaches consensus: all nodes agree to keep a single authenticated copy of the ledger.

## What does it mean to mine?

As I mentioned earlier, the miners are nodes that participate in the network and are in charge of mining: all the operations that are done in the network are grouped in blocks, and to validate them the miners must find a kind of computer key called hash. These are mathematical formulas that synthesize in a few characters a lot of information. No two hashs are alike, and can not be modified. Each block has a new hash and hash of the immediately preceding block. Everything is linked, hence the reason for chain.

Whenever a miner finds a valid hash (must meet a number of conditions), it will receive his reward in cryptocurrency, after verifying at least 51% of the miners.
If not clear, the above process is called mining.

## What is Bitcoin?

Bitcoin is a consensual network that allows a new payment system and a completely digital currency. It is the first network among decentralized payment pairs driven by its users without a central authority or intermediaries, in other words, it is the first known blockchain implementation.

## What is Ethereum? What is Ether?

[Ethereum](https://ethereum.org/) is a decentralized platform that allows the execution of smart contracts between peers. Any developer can create and publish distributed applications that runs smart contracts.

[Ether](https://ethereum.org/ether) is a cryptocurrency like Bitcoin and it's the required fuel for the distributed applications to operate on the platform of Ethereum. Ether is the incentive that prompts developers to write quality applications (wasteful code consumes more Ether) and the network stays healthy (resources contributed are rewarded with Ether).

## What is Solidity?

[Solidity](https://github.com/ethereum/solidity) is a contract-oriented programming language, which is used to create smart contracts on different blockchain platforms (Example: Ethereum).

## What is Truffle?

It is a development framework for Ethereum which allows, among other things, to compile, link and deploy intelligent contracts. It also supports the creation of automated tests.

## How to build your development environment to create and test Smart Contracts?

This and other questions will be answered soon in new publications.

## Conclusion

Blockchain presents itself as a clearly disruptive technology, which is being adopted by different organizations for different purposes. Its impact clearly goes beyond the financial industry.

Since its first implementation has evolved, allowing the creation of new platforms among which, in addition to Ethereum, we can name [Corda](https://www.corda.net/), [Hyperledger](https: // www.hyperledger.org/) and [Lisk](https://lisk.io/) as the most resonant.

As they say, not everything that shines is gold, there are still issues to improve, such as the number of transactions per minute that is far from what is required at the corporate level and the cost of mining in terms of energy consumption that is also high . Blockchain is not the solution to all the problems of humanity, but to my humble understanding, it is a clear possibility to remove the intermediaries putting before us an opportunity of improvement to evaluate and to implement, thing that many of the important actors are doing.

Soon I will be sharing my experience by entering into this new paradigm, with a focus more oriented to the development of software.