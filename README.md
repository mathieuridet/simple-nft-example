# 🖼 Simple NFT Example

A simple ERC-721 NFT smart contract deployed to Sepolia testnet, built with [Scaffold-ETH 2](https://github.com/scaffold-eth/scaffold-eth-2).

## 🚀 Features
- ERC-721 compliant NFT contract
- Mint NFTs on the Sepolia testnet
- View NFTs via a connected wallet
- Uses Alchemy as RPC provider

## 📦 Tech Stack
- Solidity
- Hardhat
- React / Next.js (Scaffold-ETH 2)
- Ethers.js
- MetaMask

## 🔗 Deployed Contract
- **Network:** Sepolia Testnet
- **Address:** `0x...`  
- **Etherscan:** [View on Etherscan](https://sepolia.etherscan.io/address/0x...)

## 🛠 How to Run Locally
```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/simple-nft-example.git
cd simple-nft-example

# Install dependencies
cd packages/hardhat && yarn install
cd ../nextjs && yarn install

# Start local frontend
yarn dev
