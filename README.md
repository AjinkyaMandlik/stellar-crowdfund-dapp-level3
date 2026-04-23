# 🌟 Stellar Crowdfund dApp
### 🚀 Level 3 – Orange Belt Submission

A production-ready decentralized crowdfunding application built on the Stellar Testnet using Soroban smart contracts. This dApp enables users to connect multiple wallets, donate XLM, view real-time campaign progress directly from the blockchain, and includes robust frontend testing.

## 🌐 Live Demo
https://stellar-crowdfund-dapp.netlify.app/

<img width="1348" height="639" alt="Screenshot 2026-04-23 213924" src="https://github.com/user-attachments/assets/b7194db5-6cb9-457b-b87a-126300157f3e" />


## 🎥 Demo Video
👉 https://drive.google.com/drive/folders/1I6nBC42i2FF8Q7kbtWVpo_HMe1bYZlhX

## 🎯 Objective
To build a decentralized application that:
- Supports multi-wallet integration
- Interacts with a deployed smart contract
- Displays real-time blockchain data
- Handles transactions and errors effectively
- **Includes a comprehensive Jest Testing Suite (Level 3 Requirement)**

## 🚀 Core Features

### 🔗 Multi-Wallet Integration
Integrated using `stellar-wallets-kit`.
Supports:
- Freighter (mandatory)
- Extensible for other Stellar wallets
- Connect & disconnect functionality
- Displays connected wallet address

### 📜 Soroban Smart Contract
**Contract ID:** `CAXJ47NQ4U4BDLNARPTPBUXGCKSX7U2TP3CEEKIAJYRQ6D3TFDGFAAYS`
**Functions:**
- `donate(amount)` → Accepts XLM and updates total funds
- `get_total_funds()` → Returns current campaign balance
**Events:**
- Emits `Donate` event for each transaction

### 🔄 Real-Time Data Synchronization
Uses Soroban RPC (`getEvents`) — No backend required.
- Live total funds update
- Dynamic donor leaderboard
- Automatic UI refresh after transactions

### 💸 Transaction Handling
Tracks transaction lifecycle:
- ⏳ Pending
- ✅ Success (with Confetti animation 🎉)
- ❌ Failed

### ⚠️ Error Handling
Handles cases:
- ❌ Wallet not found
- ❌ Transaction rejected by user
- ❌ Insufficient balance

### 🧪 Jest Testing Suite (Level 3 Feature)
Comprehensive frontend testing for core dApp logic:
- Campaign Initialization defaults
- Donation calculation logic
- Progress percentage math
- Edge cases (Max funding caps)
  
-🧪 Testing (Jest)
 -Total Test Suites: 2
 -Total Tests: 8
 -Status: ✅ All Passing
## 📸 Test Output
<img width="758" height="569" alt="image" src="https://github.com/user-attachments/assets/4397e7ac-823e-4c1b-9c8e-86097a604efd" />


## 🎨 UI / UX
- Clean modern glassmorphism design (Tailwind CSS)
- Responsive layout
- Interactive components with hover states
- Confetti animation on success
- Real-time progress bar

## 📂 Project Structure
```text
stellar-multiwallet-dapp/
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── hooks/
│   │   ├── services/
│   │   ├── utils/
│   │   ├── __tests__/
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── tests/
│   └── package.json
│
├── contracts/
│
└── README.md
```

## 🧪 Testnet Details
- **Network:** Stellar Testnet
- **Explorer:** [https://stellar.expert](https://stellar.expert)
- **Fund Wallet:** [Friendbot](https://friendbot.stellar.org)

## 💻 Running Locally

### Prerequisites
- Node.js installed
- Freighter Wallet installed (set to Testnet)

### Installation
```bash
git clone https://github.com/AjinkyaMandlik/stellar-crowdfund-dapp-level3.git
cd stellar-multiwallet-dapp
npm install --prefix frontend
npm run dev
```
Open: 👉 http://localhost:5173

### Running Tests
Ensure you are in the root directory then run:
```bash
npm test
```

## 🛠 Tech Stack
- **Frontend:** React (Vite)
- **Styling:** Tailwind CSS
- **Smart Contract:** Soroban (Rust)
- **Blockchain SDK:** `@stellar/stellar-sdk`
- **Wallet Integration:** `stellar-wallets-kit`
- **Testing:** Jest

## ✅ Level 3 Orange Belt Requirements Checklist
- [x] All Level 1 & 2 requirements met
- [x] Multi-wallet integration
- [x] Meaningful frontend testing (Jest installed & running 8 passing tests)
- [x] Clean, component-based folder structure
- [x] Error handling & Real-time updates

## 👨‍💻 Author
**Ajinkya Mandlik**

⭐ If you found this project useful, consider giving it a star!
