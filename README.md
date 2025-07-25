# EVM Stablecoin Launch

This project demonstrates the launch of a stablecoin on an EVM-compatible blockchain using Solidity.

## 🧾 Overview

The repository contains the smart contract code and deployment logic for a basic stablecoin, built and deployed on EVM-compatible networks such as Ethereum or Binance Smart Chain.

## 🛠 Tech Stack

- **Solidity** – Smart contract programming language.
- **Hardhat** or **Truffle** – For compiling, testing, and deploying contracts (customize based on actual usage).
- **EVM-compatible Chains** – Ethereum, BSC, Polygon, etc.

## 🚀 Features

- ERC-20 compliant stablecoin
- Minting and burning functionality
- Owner-controlled supply mechanisms
- Designed for deployment on any EVM-compatible chain

## 📁 Structure

```
contracts/        # Solidity smart contracts
scripts/          # Deployment and management scripts
test/             # Test cases
README.md         # Project overview
```

## 🧪 Usage

1. Install dependencies:
   ```bash
   npm install
   ```

2. Compile the contracts:
   ```bash
   npx hardhat compile
   ```

3. Run tests:
   ```bash
   npx hardhat test
   ```

4. Deploy to a network:
   ```bash
   npx hardhat run scripts/deploy.js --network <network-name>
   ```

## 📜 License

This project is licensed under the MIT License.

---

Created by [@topsecretagent007](https://github.com/topsecretagent007)

