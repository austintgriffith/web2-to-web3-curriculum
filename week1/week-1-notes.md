## 👩‍🔬 Becoming A Power User 

The first step to starting as a developer in the web3 ecosystem is first to become a Power User! You should begin by getting hands-on & using the tools which will give you a much greater understanding of what you can do and what the crypto space is all about. In this section, we're talking about the tools in the crypto space, using them and helping you become an Ethereum power user.

## Day 2: Wallets

#### Crypto Wallets

As a user, it all starts with a [crypto wallet](https://www.coinbase.com/learn/crypto-basics/what-is-a-crypto-wallet), which is what allows you to talk to the blockchain. It gives you the tools you need to interact with cryptocurrencies. A crypto wallet generates a private & public key. A crypto wallet's main functionality is storing the keys and signing transactions.

- 🔓 A **public key**, as the name indicates, is public. If you give someone your public address, they can send you cryptocurrencies.
- 🔐 A **private key** is like your password. You should keep it safe and NEVER share it with anyone. Anyone with your private key has full access to your wallet. It's hard to remember and store this number; that's where seed phrases come in. It's a phrase generated from the private key that's human-readable and easier to store. 

There are Custodial Wallets vs Non-Custodial Wallets.

- ** Custodial Wallets** : A third-party (generally an exchange such as Coinbase, Binance, or Robinhood) has your private keys and signs transactions on your behalf. You trust the third party to hold your keys and give them your information.
- ** Non-Custodial Wallets** : The user owns the private keys; there is no third party in between. Therefore, the user is the only person with the private key and/or seed phrase; no one else should have this information. 

On a custodial wallet, you have limited functionality. You can do what the platform allows you to do, mainly to buy and sell coins/tokens. However, when you want to play a crypto game, this is generally not possible.

🌟 One of the most popular non-custodial crypto wallets is [Metamask](https://metamask.io/), head over to the website to set up your wallet. Another popular wallet is [Rainbow](https://rainbow.me/), that's a mobile wallet.  

After you've set up Metamask, you can see your public address on the top. This is like your bank account number; it's a public account number you can share to receive funds. 

#### Transactions 

Everything you do on ethereum is a transaction. For example, 
when you send some tokens from one account to another it will be addded to the ledger as a transaction. 

[Etherscan](https://etherscan.io/) is a block explorer for Ethereum, which records all the transactions and display them in an easy way.

#### Gas Fees 

There will be a transaction fee associated with making the transfer. This is called a [Gas Fee.](https://ethereum.org/en/developers/docs/gas/) Every transaction on the blockchain has a cost. So when you want to send tokens, you need to pay the price called the gas fee. Gas is the unit's measure to denote the transaction cost. 

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

#### Metamask Settings

You are able to edit the gas fee on Metamask: gas limit, max priority fee, max fee(gwei)

In Ethereum, every transaction has a nonce. Nounce is an abbreviation for “number used once." Each time you make a transaction the nonce increases by 1. The transactions must be executed in order, and the order is determinded by the nounce. This prevents the double-spend problem.  

#### Layer 2

The goal of the scaling solutions is to increase the speed and lower the cost without giving away the security and the security or decentralization of the main blockchain, also known as the L1 base chain. 

There are various kinds of [scaling solutions](https://ethereum.org/en/developers/docs/scaling/) for Ethereum that are being used and researched.

Layer 2 is a type of scaling solution that provices faster and quicker transaction, uses the security of Ethereum.

[Optimism](https://www.optimism.io/) is an optimistic rollup layer2 Solution. A rollup combines a bunch of transactions into one, and it will only submit that one transaction to the Layer 1 blockchain. This way, it avoids congestion on the main chain. It basically takes some transactions and rolls them up to one, hence the name "rollups."  

#### Decentrazlized Finance (DeFi)

[DeFi](https://www.coinbase.com/learn/crypto-basics/what-is-defi) is financial technology thats based on cryptocurrency. There aren't any central intermediaries, instead the transactions are peer-to-peer.

[Aave](https://aave.com/) is a decentralized non-custodial liquidity protocol. It allows users to manage their digital assests. Users can participate by borrowing and depositing assets. Depositing assets means that you are providing assets the liquidity pool or in other words you are supplying money to the smart contract. 

[Matcha](https://matcha.xyz/) is a DEX aggregator on Ethereum that aggregates the prices of other DEX's and merges them to a single result. 

#### Multisig 

A Multisignature(multisig) is a smart contract wallet that operates with 2 or more addresses. It requires two or more private keys to set a crypto wallet. You can define the rules to sign and execute transactions. Fo example, you can have a wallet with 5 signers and 4 signers need to approve for a transactions to be executed. 

[Gnosis Safe](https://gnosis-safe.io/) is a multisig on Ethereum. You can manage all your digital assets on a multisig wallet. 

### 🥅 Goals TODO
- [ ] Bridge some tokens to Optimisim 
- [ ] Setup a multi-sig wallet

**Deliverables**
- [ ] Submit your transactions of Gnosis-safe 

