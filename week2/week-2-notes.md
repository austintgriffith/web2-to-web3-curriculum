## 👩‍🚀 Scripting and Deeper Concepts 

In this section, we'll start programming! It goes from writing scripts to talking to the blockchain to building Decentralized Applications(dApps). The topics covered included Providers, Signers, ethers.js, Hardhat, Scaffold-eth & many more! 

Here are the Scripts for the [week](https://github.com/carletex/week2-scripts). 

## Day 1: Scripting with ethers.js, Providers, Signers, Wallets, etc...

[Ethers.js](https://docs.ethers.io/v5/): javascript library for interacting with the Ethereum Blockchain. It's a very well documented & lightweight library. 
Another popular library is [web3.js](https://web3js.readthedocs.io/en/v1.7.5/)

[Providers](https://docs.ethers.io/v5/api/providers/): A Provider is like an interface that enables you to talk to the Ethereum node. You can ask the Provider for information on the network. It only has read access to the blockchain. Any node on the network can be a provider. You can have your own node or use a node provider such as [Infura](https://infura.io/) or [Alchemy](https://www.alchemy.com/). 

[Signers](https://docs.ethers.io/v5/api/signer/): A signer is an Ethereum account that can sign a message & send a transaction. A signer has write access; it can change the state of the network. 

*Make sure to check which network you're on. For resolving ENS, you'll need to use a mainnent provider; when you want to make other transactions, you'll need to connect to other networks if you're on a testnet or L2.*

### 🥅 Goals
- [ ] Use a Provider: Get block number, ENS resolver 
- [ ] Create a new wallet w/ethers.js
- [ ] Use a signer 
- [ ] Make sure to have the .env file 

----

## Day 2: 

[Contract](https://docs.ethers.io/v5/api/contract/contract/): abstraction of code that has been deployed to the blockchain. If you want to talk to a contract, your making a transaction that interacts with the smart contract

[Application Binary Interface(ABI)](https://docs.ethers.io/v5/api/utils/abi/): is the interface between two program modules. Simply put, ABI is like the API (Application Programming Interface) in the Ethereum world. It defines the methods and structures to interact with the smart contract.

Make sure:
- To create a new Wallet & private key for your smart contracts
- NEVER EVER commit your .env file to GitHub! 

### 🥅 Goals
- [ ] Interact with a Smart Contract (eg: Standford NFT, DAI) 
- [ ] Testing transactions: Send TestNet ETH
- [ ] Go through the utils file in the week-2 folder

----

## Day 3: Intro to Ethereum Clients & Hardhat

[Ethereum Nodes and Clients](https://ethereum.org/en/developers/docs/nodes-and-clients/): Ethereum is a distributed network of computers, called nodes, that run software to verify the blocks and the transaction data. This software application is called a client; the computer running it is an Ethereum node. 
  - There are different types of clients, and you can read more [here](https://ethereum.org/en/developers/docs/nodes-and-clients/client-diversity/). 
  - Read more about nodes & [run your own node](https://ethereum.org/en/developers/docs/nodes-and-clients/run-a-node/). Running your own node provides various benefits, opens new possibilities, and helps support the ecosystem.
    - [How to run a light node with geth](https://ethereum.org/en/developers/tutorials/run-light-node-geth/)

[Hardhat](https://hardhat.org/hardhat-runner/docs/getting-started#overview) is a development environment to compile, test and debug your Ethereum software. You can create a complete developer environment and have your own local blockchain to try your smart contracts. 

**Be careful: Do not deploy to mainnet with the default hardhat accounts!**

### 🥅 Goals
- [ ] Setup your geth light client 
- [ ] Use your own local node as a provider, and get the block number from your local node & another node provider (Infura, Alchemy etc.)
- [ ] Hardhat Setup & Testing smart contacts with Hardhat
- [ ] Verify your smart contract on Etherscan 

---

## Day 4: Solidity & Testing with Hardhat  

Learn Solidity on [Solidity by Examples](https://solidity-by-example.org/).

[Remix Ide](https://remix.ethereum.org/) is a browser-based IDE for Ethereum, it's convenient to get started with as you don't need any setup.

### 🥅 Goals
- [ ] Try different concepts on Solidity
- [ ] Write a smart contract and the tests for it

---

## Day 5: 🏗 Scaffold-eth Intro & Solidity Recap  

[Scaffold-Eth](https://github.com/scaffold-eth/scaffold-eth) is a template for building Decentralized Applications(dApp's). It provides rapid prototyping on Ethereum. With Scaffold-ETH, you can change the smart contract, and the changes will automatically reflect on your front end. This way, you can see and test your smart contract changes from the UI.

[Solidity Code Examples](https://solidity-by-example.org/), which you can try on your smart contracts.

[The Ethernaut](https://ethernaut.openzeppelin.com/) is a game to learn about smart contract vulnerabilities. It's a game where users hack the smart contract to move on to the next levels.  

### 🥅 Goals
- [ ] Get Scaffold-eth and tinker with Solidity 

