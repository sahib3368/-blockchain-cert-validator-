# 🚀 Blockchain Certificate Validation System
BTech CSE Final Year Project - Sharda University

## Live Demo
Frontend: https://your-project.vercel.app  
Blockchain: Sepolia Testnet  
Backend: Render.com  

## Features
✅ Certificate issuance with QR codes  
✅ Real-time verification via blockchain  
✅ Tamper-proof using SHA256 + IPFS  
✅ Admin revocation system  
✅ Mobile QR scanner  

## Tech Stack
• Solidity Smart Contracts (Truffle/Ganache)  
• React.js Frontend (Vercel)  
• Node.js Backend (Render)  
• IPFS File Storage (Pinata)  
• Sepolia Testnet (Infura)

## Quick Start
```bash
npm install -g truffle ganache
ganache
truffle migrate
cd client && npm start

**truffle-config.js**:
```javascript
module.exports = {
  networks: {
    development: {
      host: "127.0.0.1",
      port: 7545,
      network_id: "*"
    }
  },
  compilers: {
    solc: {
      version: "0.8.19"
    }
  }
};
