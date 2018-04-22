# Plain and Simple Smart Contracts

By: Ira Miller

For: [PanaFintech](http://www.panafintech.com/)

## Definition

"Smart contracts are P2P state machines." <br> - [Ira](https://iramiller.com/)

"Smart contracts are computer protocols that facilitate, verify, or enforce the negotiation or performance of a [contract](https://en.wikipedia.org/wiki/Contract), or that make a contractual clause unnecessary." - [Wikipedia](https://en.wikipedia.org/wiki/Smart_contract)

## P2P State Machine

![P2PStateMachine](

## History & Types

|Network(by age)|Scripting|Turing Complete|Encrypted|
|---------------|----------|--------------|----------|
|Bitcoin        |yes       |no            |no        |
|Bitcoin (Omni) |yes       |maybe         |no        |
|Ethereum       |yes       |yes           |no        |
|Bitcoin(RSK)   |yes       |yes           |no        |
|Lisk, others   |yes       |yes           |no        |
|Guld           |yes       |yes           |yes       |

* Scripting example is multi-sig.
* Turing Complete means able to do any computer operation.
* Encrypted for user defined objects and keyrings.

## Guld Contracts

### How It Works

* All data must be plain text files w/ PGP encrypt option.
* All data stored in (SHA1 hash) git tree
* All git commits PGP  signed w/ 2048+ bit RSA/DSA
* Each git repo must define allowed states & transformations

### Git Blockchain
