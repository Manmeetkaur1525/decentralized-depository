# Decentralized Depository

A decentralized platform for secure image upload and sharing using blockchain. This project leverages Solidity for smart contracts, React for the front end, and IPFS for decentralized storage.

## 🚀 Features
- **Decentralized Storage:** Images stored securely on IPFS.
- **Smart Contract:** Ethereum-based access control and ownership.
- **User Permissions:** Grant or revoke access to specific users.

## 🛠 Tech Stack
- **Solidity** – Smart contracts
- **React** – Front-end UI
- **IPFS** – Decentralized image storage

## 📌 Setup
### Installation
```bash
# Clone repository
git clone https://github.com/your-username/decentralized-depository.git
cd decentralized-depository

# Install dependencies
npm install

# Compile smart contract
npx hardhat compile

# Deploy contract
npx hardhat run scripts/deploy.js --network <network-name>

# Start frontend
cd client
npm install
npm start
