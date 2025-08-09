# 🖼 Simple NFT Example

A simple ERC-721 NFT smart contract deployed to Sepolia testnet, built with [Scaffold-ETH 2](https://github.com/scaffold-eth/scaffold-eth-2).

<img width="1326" height="765" alt="Capture d’écran 2025-08-09 à 13 09 47" src="https://github.com/user-attachments/assets/1ae5f67f-3572-47ab-b0c6-77921b5a5e84" />

<img width="1431" height="765" alt="Capture d’écran 2025-08-09 à 13 11 04" src="https://github.com/user-attachments/assets/7bd31bc5-1637-47a7-8635-b5ef8256a5ca" />

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
- **Address:** `0x5554d8c045c587f7B35e4451246AAbB66f0B4CFC`  
- **Etherscan:** [View on Etherscan](https://sepolia.etherscan.io/address/0x5554d8c045c587f7B35e4451246AAbB66f0B4CFC)

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
