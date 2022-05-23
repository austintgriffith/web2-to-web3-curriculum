**week 2 / day 1:** Basic scripting with EthersJS

Contextualize week 2:
- Week1: We used existing front-end tools (metamask, etherscan, uniswap, ENS domains, Aaave) to talk with Ethereum / Smart contracts.
- (Week2): We are going to learn how to talk «directly» with Ethereum / Smart contracts.
- Week3: We'll be deploying our own smart contract & front-end apps.

What's EtherJS (mention alternatives like web3js)

Quick Environment setup guide:
  - NodeJS & npm (recommending using a node version manager like [n](https://github.com/tj/n))
  - npm init & npm i ethers

Providers. (read-only)
  - Get latest block
  - ENS resolve & reverse lookup
  - Get balance. 
    - BigNumbers! formatEther / parseEther

Wallets
 - Load wallet from mnemonic. Accounts: Derivation path.
 - Create wallet mnemonic from code

Signers
  (Not sure if we'll have time. Maybe we just want to explain signers, and leave the practical stuff for day2)
 - Connect signer to a provider
 - sendTransaction
