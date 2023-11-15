# 🌌 Ethereum Smart Contract Odyssey: The Good & The Attack

Step into the cosmos of Ethereum smart contracts with `Good.sol` and `Attack.sol`, two celestial bodies written in the constellation of Solidity. This odyssey is guided by unit tests, meticulously crafted in JavaScript using the Hardhat and Chai frameworks.

## 🌠 Overview

- **Good.sol**: This contract is a beacon in the blockchain universe. It illuminates a simple auction mechanism where users can ascend to the status of `currentWinner` by sending more Ether than the `currentAuctionPrice`.

- **Attack.sol**: This contract is your spacecraft. It's engineered to interact with the `Good` contract. Its function, `attack`, propels a user to the `currentWinner` status in the `Good` contract by sending more Ether than the `currentAuctionPrice`.

The unit test is your star map. It verifies whether the `Attack` contract can maintain its `currentWinner` status, preventing other users from claiming it after the `Attack` contract has won the auction. This is akin to a Denial of Service (DoS) attack, where the `Attack` contract aims to perpetually remain the auction winner.

## 🚀 Requirements

- Node.js
- npm
- Hardhat
- Ethereum wallet

## 🛸 Installation

1. Clone this repository to your local machine.
2. Run `npm install` to install the necessary dependencies.
3. Run `npx hardhat compile` to compile the contracts.

## 🌌 Testing

Run `npx hardhat test` to run the unit tests and ensure your odyssey is on the right path.

## ⚠️ Caution

Interacting with other contracts can have security implications. It's crucial to understand the code of the `Good` and `Attack` contracts thoroughly. Always consult with a Solidity expert or conduct a thorough audit before using these contracts in a production environment.

---
