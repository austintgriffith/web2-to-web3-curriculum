## 👩‍🚀 Scripting and Deeper Concepts 

Here are the Scripts for the [week](https://github.com/carletex/week2-scripts). 


## Day 1: Scripting with ethers.js, Providers, Signers, Wallets, etc..

[Ethers.js](https://docs.ethers.io/v5/): javascript library that helps you communicate with Ethereum. Helper functions, send value around, format. It’s a very lightweight library.
Another popular js libary is web3.js

[Provider](https://docs.ethers.io/v5/api/providers/): You can ask the provider for information on the network. A provider only has read access to the blockchain. Any node on the network can be a provider. You can have your own node or use an node provider such as Infura or Alchemy. 

[Signer](https://docs.ethers.io/v5/api/signer/): Sign a message and send a transaction. A signer has write access, it can change the state. 

*Make sure to check which network you’re on. For resolving ENS you’ll need to use a mainnent provider, when you want to make other transactions you’ll need to connect to other networks if you’re on a testnet or L2.*

### 🥅 Goals
- [ ] Use a Provider: get block number, ens resolver 
- [ ] Create a new wallet w/ethers.js
- [ ] Use a signer 
- [ ] Make sure to have the .env file 

**Deliverables**
- [ ] TO DO 

----

## Day 2: 

[Contract](https://docs.ethers.io/v5/api/contract/contract/): abstraction of code that has been deployed to the blockchain. If you want talk to a contract your making a transaction that interacts with the smart contract

[Application Binary Interface(ABI)](https://docs.ethers.io/v5/api/utils/abi/): is the interface between two program modules. Simply put, ABI is like the API (Application Programming Interface) in the Ethereum world. It defines the methods and structures to interact with the smart contract.

Make sure:
- to create new wallet & private key for your smart contracts
- don’t commit your .ENV file to GitHub! 

### 🥅 Goals
- [ ] Interact with a Smart Contract (eg: Standford NFT, DAI) 
- [ ] Testing transactions: Send TestNet ETH
- [ ] Go through the utils file in the week-2 folder

**Deliverables**
- [ ] XX

----

## Day 3: 

hard hat? testing? advanced? sign, recover, encrypt, and decrypt
https://youtu.be/7EwDOV4nEcY

### 🥅 Goals
- [ ] XX

**Deliverables**
- [ ] XX

---

## Day 4: 

solidity! primative datatypes, functions, require, mapping, - inheritance / modifiers
https://youtu.be/KjzH5EPCA-A

### 🥅 Goals
- [ ] XX

**Deliverables**
- [ ] XX

---

## Day 5: 

solidity recap and 🏗 scaffold-eth intro
[[https://youtu.be/7EwDOV4nEcY](https://youtu.be/KjzH5EPCA-A)](https://youtu.be/7pIzfm7hxQk)

### 🥅 Goals
- [ ] XX

**Deliverables**
- [ ] XX
