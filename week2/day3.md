**week 2 / day 3:** Hardhat environment

Running a local node with geth.
  - Client diversity
  - Use some day2 scripts with the local provider.

---

What's Hardhat?

Hardhat installation (with «basic template»). Check:
  - Contracts
  - Scripts
  - Tasks
  - Plugins
  - Tests
  - hardhat.config.js

Run the Hardhat Network + Node
  - **Danger!** Hardhat accounts are deterministic
  - Add hardhat account0 to metamask + add local/hardhat 31337 network

Use some of the scripts from day2 with the local network/node.
  - Get balance
  - Send ETH

Contracts:
  - Overview of Greeter.sol
  - Deploy contract locally (gotcha: hardhat vs localhost network)
  - Interact with the Greeter contract. (ethers vs hre.ethers)

Tests:
  - Explain the anatomy of a test
  - Run tests
  - Make a change to Greeter.sol
  - Fix/Add test to cover the change.

Extra: Deploy & verify a contract on rinkeby
