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

## Day 3: Intro to Ethereum Clients & Hardhat

[Ethereum Nodes and Clients](https://ethereum.org/en/developers/docs/nodes-and-clients/): Ethereum is a distributed network of computers, called nodes, that run software to verify the blocks and the transaction data. This software application is called a client, and the computer running it is an Ethereum node. 
  - There are different types of clients and you can read more [here](https://ethereum.org/en/developers/docs/nodes-and-clients/client-diversity/). 
  - Read more about nodes & [run your own node](https://ethereum.org/en/developers/docs/nodes-and-clients/run-a-node/). Running your own node provides you various benefits, opens new possibilities, and helps to support the ecosystem.
    - [How to run a light node with geth](https://ethereum.org/en/developers/tutorials/run-light-node-geth/)

[Hardhat](https://hardhat.org/hardhat-runner/docs/getting-started#overview) is a development environment to compile, test and debug your ethereum software. You can create a complete developer environment and have your own local blockchain to test your smart contracts. 

**Be careful: Do not deploy to mainnet with the default hardhat accounts!**

### 🥅 Goals
- [ ] Setup your geth light client 
- [ ] Use your own local node as a provider, and get the blocknumber from your local node & another node provider (Infura, Alchemy etc.)
- [ ] Hardhat Setup & Testing smart contacts with Hardhat
- [ ] Verify your smart contract on Etherscan 

---

## Day 4: Solidity & Testing with Hardhat  

Learn Solidity on [Solidity by Examples](https://solidity-by-example.org/).

[Remix Ide](https://remix.ethereum.org/) is a browser-based ide for Ethereum, its convenient to get started with as you don't need any setup.

### 🥅 Goals
- [ ] Try different conpets on Solidity
- [ ] Write a smart contract and the tests for it

---

## Day 5: 🏗 Scaffold-eth Intro & Solidity Recap  

[Scaffold-Eth](https://github.com/scaffold-eth/scaffold-eth) is a template for building Decentralized Applications(dApp's). It provides rapid prototyping on Ethereum. With Scaffold-ETH, you can change the smart contract, and the changes will automatically reflect on your frontend. This way, you can see and test your smart contract changes from the UI.

[Solidity Code Examples](https://solidity-by-example.org/) which you can try on your smart contracts.

[The Ethernaut](https://ethernaut.openzeppelin.com/) is a game to learn about the smart contract vulneratibilities. It's a game where users hack the smart contract to move onto the next levels.  

### 🥅 Goals
- [ ] Get Scaffold-eth and tinker with Solidity 

