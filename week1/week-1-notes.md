## 👩‍🔬 Becoming A Power User 

**TO DO: add intro**

## Day 2: Wallets

#### Crypto Wallets

A **crypto wallet** is what allows you to talk to the blockchain network. It gives you the tools you need to interact with cryptocurrencies. Examples of cryptocurrency wallets are Metamask, Ledger, Rainbow.

A crypto wallet generates a private key and a public key. The main functionality of a crypto wallet is to store your keys and sign transactions. 

-	A public key, as the name indicates is public. If you give your public address or associated crypto addresses, then people can send you cryptocurrencies. 
-	🔐 A private key is like your password. You should keep it safe and never share it with anyone. Anyone with your private key has full access to your wallet. 
Its just 256 digit binary number. It’s hard to remember and store this number, thats where seed pharses come in. 

A mnemonic (also known as a seed phrase) is a way to restore your private key. It's is a 12-word combination which can be used generate private keys. 
Seed phrases creates a convienet way to save to restore your crypto wallet. 

Note: do not share your seed phrase or private key with anyone! Whomever has access to these, has full access to your account.

Types of crypto wallets: **Custodial Wallets vs Non-Custodial Wallets**

-	Custodial Wallets: A third-party (generally an exchange such as Coinbase, Binance, Robinhood) has your private keys and signs transactions on your behalf. You trust the third party to hold the keys for you.
-	Non-Custodial Wallets: The user owns the private keys of the non-custodial wallet. Unlike a custodial wallet, there is no third party in between. Therefore, the user is the only person that has the private key and/or seed phrase. There is no customer servie for non- custodial wallets and no one should ask you seed phrase or private keys. 

#### Transactions 

Everything you do on ethereum is a transaction. For example, 
when you send some tokens from one account to another it will be addded to the ledger as a transaction. 
[Etherscan](https://etherscan.io/) is a block explorer for Etherum which records all the transactions to display them in a easy way. 

#### Gas Fees 

Every transaction on the blockchain has a cost. So when you want to send tokens you need to pay the price called **gas fee**. Gas is the measure of the unit to denote the cost for a transaction. Accordingly, gas fees are the fees that are paid to the network to process the transactions.

On Ethereum, gas fees are paid in ETH and denoted in gwei. 

### 🥅 Goals
- [ ] Setup a metamask wallet 
- [ ] Add Test Netwoks to metamask 
- [ ] Get some Testnet ETH

**Deliverables**
- [ ] Send you Testnet transactions **TO DO**
- [ ] Send your wallet address to **TO DO**

----  
  
  
## Day 3: ENS, DEX, Identity, Inventory, Sybil

#### Decentralized App(dApp) 

A dApp is just like any software application- any website or phone app. The difference is that the backend code runs on a decentralized network such as a peer to peer network or a blockchain. So an application on Ethereum is a dApp.

We'll use our wallet to interfere with web3 services. Our identity & inventory will follow you from app to app. 

#### ENS 

The wallet address is a 42-character hexadecimal address. This is very hard to remember. That's where ENS comes in. [Etherum Name Service (ENS)](https://docs.ens.domains/) is a lookup service built on the Ethereum. It's like Domain Name Service(DNS) in the Ethereum world. Just as DNS takes the IP address and maps it to a human-readable domain name, ENS takes the crypto address and maps it to a human-readable string. 

#### Decentrazlized Exchange & Centralized Exchange 

- Centralized Exchange: An exchange thats owned by one entity. They allow you to buy and sell crypto currencies. 
- Decentralized Exchange: An exchange that allows for peer-to-peer cryptocurrency transactions. There are no intermediaries but instead its based on smart contracts. 

[Uniswap](https://uniswap.org/) is a Decentralized Exchange on the Ethereum Blockchain. 

#### ERC 20

ERC-20 is a standard for smart contracts that create fungible tokens on the Ethereum blockchain. ERC stands "Ethereum request for comment" and 20 is the token identifier. 

DAI is an ERC20 token thats a stablecoin. You can read on how DAI works [here](https://docs.makerdao.com/getting-started/maker-protocol-101)

There are more ERC smart contracts. For example, the standard for creating a non-fungible token(NFT) is ERC-721.

### 🥅 Goals
- [ ]  Get an ENS name & set your primary ENS name
- [ ]  Have a look at Uniswap 
- [ ]  Look at Zapper.fi 

**Deliverables**
- [ ] Send you ENS transaction(s) **TO DO**

----  
  
## Day 4: NFTs! ERC20 vs ERC721, IPFS, Metadata

#### NFT

NFT stands for Non-Fungible Token.
* Non-fungible: Non-fungible refers to goods that have unique properties and can not be changed with one another. 
* Token: Token is a digital asset living on top of the blockchain.

NFT's are unique digital assets on the blockchain. They are each one of a kind; this allows for tracking the ownership. NFT's are created by running the code on the smart contract. This process is also called "minting."

ERC-721 is a standard type of smart contract that creates NFTs on Ethereum. Here's a sample NFT which you can find over [here.](https://github.com/carletex/sanford-stout-nft)

[Opensea](https://opensea.io/) is an NFT Marketplace where users can buy/sell NFTs. 
  
#### Storage Types 

In the NFT smart contract we define where the metadata of the NFT is located. There are different ways to store the data in the NFT. Basically, there is a seperate storage layer that holds the content. 

[IPFS](https://ipfs.io/) stands for InterPlanetary File System. It is a distributed system for storing and accessing files, websites, applications, and data.

SVG stands for Scalable Vector Graphics, it renders the content in the smart contract. Having the content on the smart contract allows to make things that are more composable.

There are also centralized storage options to store the data and the images. 

### 🥅 Goals 
- [ ] Mint an NFT from Etherscan??? **to do: rinkeby??** 
- [ ] Have a look at NFT marketplace(s) 
- [ ] Check out your inventory on Zapper.fi 

**Deliverables**
- [ ] Submit you NFT transaction **to do**
 
----  
  
## Day 5: Stuck Transaction, Gas Limits, Multisigs, L2s, Lending

#### Transactions
- Edit the gas fee on metamask : gas limit, max priority fee, max fee(gwei)
- Nounce is an abbreviation for “number used once." 

#### Layer 2
Faster and quicker transaction, settels to Ethereum and uses the security of ethereum.
Optimisim 

quixotic: optimisim nft marketplace 

#### Lending
- supply money to the contract --> lock as collateral 
  
#### ERC20 Approve Pattern 
dai to eth on matcha.xyz

#### Multisigs
gnosis safe 
smart contract wallet 
sign & sign + execute 
use a multisig to make a transaction: move money with a vote from the multisig 

### 🥅 Goals TODO
- [ ] Deposit and Borrow on Aave 
- [ ] Bridge some tokens to Optimisim 
- [ ] Setup a multi-sig wallet

**Deliverables**
- [ ] Submit your transactions of gnosis safe **TO DO**

