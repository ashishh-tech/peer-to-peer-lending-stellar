# 🚀 Stellar Soroban P2P Lending Smart Contract

## 📌 Project Description

This project is a decentralized Peer-to-Peer (P2P) lending platform built on the Stellar blockchain using Soroban smart contracts. It allows users to lend and borrow funds directly without intermediaries, ensuring transparency, security, and low transaction costs.

---

## ⚙️ What it does

The smart contract enables:

* Lenders to create loan offers
* Borrowers to accept loans
* Borrowers to repay loans
* Public access to loan details

All operations are executed on-chain using Soroban smart contracts, ensuring trustless transactions.

---

## ✨ Features

* 🔗 Fully decentralized lending system
* 👛 Wallet-based authentication (no login required)
* 💸 Loan creation and acceptance
* 🔄 Loan repayment tracking
* 📊 Transparent loan data stored on-chain
* ⚡ Fast and low-cost transactions using Stellar

---

## 🛠️ Tech Stack

* Stellar Blockchain
* Soroban Smart Contracts (Rust)
* Stellar CLI
* Freighter Wallet

---

## 🚀 How to Run Locally

1. Install Stellar CLI
2. Clone this repository
3. Build the contract:

   ```
   cargo build --target wasm32-unknown-unknown --release
   ```
4. Deploy using Stellar CLI

---

## 🌐 Deployed Smart Contract Links

### 🔗 **Contract Explorer (Stellar Lab)**
https://lab.stellar.org/r/testnet/contract/CAEHJM2NVDC7IPHICCPAVSNFF3MN4SK4F5K5O6V5T3MSDQBULBLNLUCB

### 🔗 **Transaction Details (Stellar Expert)**
https://stellar.expert/explorer/testnet/tx/3f0794b14fb131c81e5982925f4c971367b6efbdd314d6848bd17cd4c38a1688

### **Contract ID**
```
CAEHJM2NVDC7IPHICCPAVSNFF3MN4SK4F5K5O6V5T3MSDQBULBLNLUCB
```

**Network:** Testnet  
**Deployment Date:** Thu, Mar 19, 2026, 08:10:30 UTC

---

## 📁 Project Structure

This repository uses the recommended structure for a Soroban project:

```text
.
├── contracts
│   └── hello-world
│       ├── src
│       │   ├── lib.rs
│       │   └── test.rs
│       └── Cargo.toml
├── Cargo.toml
├── README.md
└── EXPLORER_LINKS.md
```

- New Soroban contracts can be put in `contracts`, each in their own directory.
- Contracts should have their own `Cargo.toml` files that rely on the top-level `Cargo.toml` workspace for their dependencies.
- Frontend libraries can be added to the top-level directory as well.

---

## 📌 Future Improvements

* Interest rate mechanism
* Collateral support
* Default penalties
* UI Dashboard (React + Web3 integration)
* Multi-asset lending support

---

## 👨‍💻 Author

Ashish Chaurasia

---

## 📜 License

MIT License
