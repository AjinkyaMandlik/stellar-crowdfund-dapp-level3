# 🚀 Stellar Crowdfund (Level 3 - Orange Belt)

A production-ready, high-performance decentralized crowdfunding application built on the **Stellar Soroban** network. This project demonstrates advanced Web3 UX patterns, real-time ledger synchronization, and robust testing.

![Demo Placeholder](https://via.placeholder.com/800x450?text=Stellar+Crowdfund+UI+Preview)

## ✨ Key Features

- **🌐 Multi-Wallet Integration**: Seamless connection via `StellarWalletsKit` (Freighter, etc.).
- **⚡ Real-Time Sync**: Polled event listeners synchronize the UI with the blockchain every 5 seconds.
- **💾 Smart Caching**: `localStorage` integration for instant page loads and background data refreshing.
- **🎨 Premium UI/UX**:
  - Modern glassmorphism design using **Tailwind CSS**.
  - Smooth, buttery animations with **Framer Motion**.
  - Interactive confetti celebrations for successful donations.
  - Responsive layout optimized for all devices.
- **📢 Live Feedback**: Real-time toast notifications for transaction status (Pending/Success/Fail).
- **🧪 Robust Testing**: Logic verification suite powered by **Jest**.

## 🛠 Tech Stack

- **Frontend**: React 19, Vite, Tailwind CSS
- **Interactions**: `@stellar/stellar-sdk`, `@creit.tech/stellar-wallets-kit`
- **Animations**: `framer-motion`, `canvas-confetti`
- **Utility**: `lucide-react` (icons), `react-hot-toast` (notifications)
- **Testing**: Jest, React Testing Library

## 🚀 Getting Started

### Prerequisites
- Node.js (v18+)
- [Freighter Wallet](https://www.freighter.app/) extension installed

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/AjinkyaMandlik/stellar-dapp.git
   ```
2. Navigate to the frontend directory:
   ```bash
   cd stellar-multiwallet-dapp/frontend
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```

### Running Tests
To verify the campaign logic and progress calculations:
```bash
npm test
```

## 📜 Contract Details
- **Network**: Stellar Testnet
- **Contract ID**: `CAXJ47NQ4U4BDLNARPTPBUXGCKSX7U2TP3CEEKIAJYRQ6D3TFDGFAAYS`
- **Explorer**: [Stellar.Expert](https://stellar.expert/explorer/testnet/contract/CAXJ47NQ4U4BDLNARPTPBUXGCKSX7U2TP3CEEKIAJYRQ6D3TFDGFAAYS)

## 🎥 Demo Video
[Link to Demo Video Placeholder]

---
*Built with ❤️ for the Stellar Developer Program.*