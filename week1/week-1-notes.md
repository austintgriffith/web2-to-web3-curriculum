## 👩‍🔬 Becoming A Power User 

The first step to starting as a developer in the web3 ecosystem is first to become a Power User! You should begin by getting hands-on & using the tools which will give you a much greater understanding of what you can do and what the crypto space is all about. In this section, we're talking about the tools in the crypto space, using them and helping you become an Ethereum power user.

## Day 2: Wallets

#### Crypto Wallets

As a user, it all starts with a [crypto wallet](https://www.coinbase.com/learn/crypto-basics/what-is-a-crypto-wallet), which is what allows you to talk to the blockchain. It gives you the tools you need to interact with cryptocurrencies. A crypto wallet generates a private & public key. A crypto wallet's main functionality is storing the keys and signing transactions.

- 🔓 A **public key**, as the name indicates, is public. If you give someone your public address, they can send you cryptocurrencies.
- 🔐 A **private key** is like your password. You should keep it safe and NEVER share it with anyone. Anyone with your private key has full access to your wallet. It's hard to remember and store this number; that's where seed phrases come in. It's a phrase generated from the private key that's human-readable and easier to store. 

There are Custodial Wallets vs Non-Custodial Wallets.

- **Custodial Wallets** : A third-party (generally an exchange such as Coinbase, Binance, or Robinhood) has your private keys and signs transactions on your behalf. You trust the third party to hold your keys and give them your information.
- **Non-Custodial Wallets** : The user owns the private keys; there is no third party in between. Therefore, the user is the only person with the private key and/or seed phrase; no one else should have this information. 

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

A dApp is just like any software application- any website or phone app. The difference is that the backend code runs on a decentralized network such as a peer-to-peer network or a blockchain. So an application on Ethereum is a dApp.

We'll use our wallet to interfere with web3 services. Our identity & inventory will follow you from app to app. 

#### ENS 

The wallet address is a 42-character hexadecimal address. Unfortunately, this is very hard to remember for humans. 

That's where [Ethereum Name Service (ENS)](https://ens.domains/) comes in. It's a lookup service built on Ethereum. It's like Domain Name Service(DNS) in the Ethereum world. A DNS takes the IP address and maps it to a human-readable domain name; ENS takes the crypto address and maps it to a human-readable string.

When you want to receive money into your account, you can send your ENS name instead of sending that complicated and long address. "name.eth" for example, I can send someone this, and they can send me coins/tokens on Ethereum. This provides a basic form of identity. 

You can head over to get yourself an ENS from the [app](https://app.ens.domains/). It's also possible to do a search of an ENS on Etherscan and see the transactions. 

#### Decentrazlized Exchange & Centralized Exchange 

- **Centralized Exchange:** An exchange that's owned by one entity. They allow you to buy and sell cryptocurrencies. Coinbase, Binance, and Robinhood are popular examples of Centralized Exchange platforms. 
- **Decentralized Exchange:** An exchange that allows for peer-to-peer cryptocurrency transactions. There are no intermediaries. Instead, it's based on smart contracts. [Uniswap](https://uniswap.org/) is a Decentralized Exchange on the Ethereum Blockchain. It is one of the most popular platforms to trade cryptocurrencies. 

It's also important to note the difference between coin and token.
- A **coin** exists on its own blockchain. It is a digital representation of money for that blockchain. BTC, ETH or SOL are cryptocurrency coins; they each have their own blockchain.
- A **token** functions on top of an existing blockchain via smart contracts. NFTs are a type of tokens. 
Basically, coins have their own blockchain and are used as a medium of exchange, whereas tokens live on top of a blockchain and can have different values or utilities.

#### ERC 20

**ERC-20** is a standard for smart contracts that create fungible tokens on the Ethereum blockchain. ERC stands for "Ethereum request for comment", and 20 is the token identifier. 

DAI is an ERC20 token that's a stablecoin. You can read how DAI works [here](https://docs.makerdao.com/getting-started/maker-protocol-101)

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

NFT stands for Non-fungible token, let's unpack what this actually means: 
- **Non-fungible**: Goods that have unique properties can not be changed with one another. For example, bitcoin is a fungible asset. If we each have a bitcoin and send them to each other, we'll have the same thing in the end. On the other hand, a house is non-fungible. If we decide to switch homes, we'll end up with something different.
- **Token**: In short, a blockchain is a shared and immutable ledger, and a token is a digital asset living on top of the blockchain.

NFTs are unique digital assets on the blockchain. Any digital asset can be an NFT; the most popular types are Collectibles and Art. We also see Writing NFTs and Music NFTs. 

- Art is self-explanatory. Artists have the chance to create their work on the blockchain and can directly reach their buyers. 
- Collectibles, as the name indicates, are a collection of assets in the format of an NFT.
Think of these as Pokemon cards or even penny collections.

Other use cases for NFT's include domain names, gaming, music, ticketing... (There can be many more applications which we have not even discovered yet.)

NFT's are created by running the code on the smart contract. This process is also called **"minting."**

[ERC-721](https://ethereum.org/en/developers/docs/standards/tokens/erc-721/) is a standard type of smart contract that creates non-fungible tokens on Ethereum. The way each token is globally unique is with the tokenId field. Therefore, for every smart contract that creates an NFT, the smart contract and the tokenId pair is different.

[Here's](https://github.com/carletex/sanford-stout-nft) a sample NFT which contract. 

The most popular NFT platform is [OpenSea](https://opensea.io/). Others are [Foundation](https://foundation.app/) and [Zora](https://zora.co/). 
  
#### Storage Types 

In the NFT smart contract, we define where the metadata of the NFT will be stored. There are different ways to store the data of the NFT. 

[IPFS](https://ipfs.io/) stands for InterPlanetary File System. It is a distributed system for storing and accessing files, websites, applications, and data.

SVG stands for Scalable Vector Graphics; it renders the content in the smart contract. Having the content on the smart contract allows for making more composable items.

There are also centralized storage options to store the data and the images. 

#### Track your wallet

With your wallet address, you can **track all that you own.** For example, let's say you have NFTs and others tokens in your wallet, staked some tokens on various platforms. Since it's all on the public blockchain, you can see all these in a central place. 

[Zapper.fi](https://zapper.fi/) is a platform that allows you to do this. So, you can easily track your wallet(s). 

You can also see what you own on [Etherscan](https://etherscan.io/), but you will not be able to see the NFT images, and the UI is focused on showing transactions rather than the assets. 

### 🥅 Goals 
- [ ] Mint an NFT from Etherscan
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

### 🥅 Goals 
- [ ] Bridge some tokens to Optimisim 
- [ ] Setup a multi-sig wallet
- [ ] Stake some tokens on Aave

**Deliverables**
- [ ] Submit your transactions of Gnosis-safe 

