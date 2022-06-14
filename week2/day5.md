**week 2 / day 5:** Scaffold-eth + more solidity concepts.

What is scaffold-eth? 
  - Tooling overview
  - Quick tour with the example contract, show the adaptable front-end
  - Example UI: react hooks / utils.

Use the [SandfordToken contract](https://github.com/carletex/week2-scripts/blob/main/day4/contracts/SanfordToken.sol) we created on day 4.

Inheritance:
  - Modify Sanford contract to use ERC20/ERC721 + Ownable
  - Show how the UI shows all the inherited methods

Interaction between contracts:
  - Until now, we've been using EOAs to interact with contracts. Always keep in mind that your contract can be called from other contracts.
  - Reentrancy example
