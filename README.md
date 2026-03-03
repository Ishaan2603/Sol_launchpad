# Solana Token Launchpad

A complete Solana token launchpad application that allows users to create custom tokens with metadata and mint them to their wallet.

IMPORTANT:- Token creation require small amount of SOL to pay solana network fees (i.e gas fee). Please ensure wallet has suffecient SOL before proceeding. 
**(Devnet SOL for testing)**

## Deployment Linnk:-

https://solana-launchpad-lac.vercel.app

## Features

- Create custom SPL tokens on Solana devnet
- Add token metadata (name, symbol, image URI)
- Mint initial supply to creator's wallet
- Modern, responsive UI with wallet integration
- Support for multiple Solana wallets

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```



### Building for Production

```bash
npm run build
```

## Usage

1. Connect your Solana wallet (Phantom, Solflare, etc.)
2. Fill in the token details:
   - Token Name
   - Token Symbol (up to 4 characters)
   - Image URL for token metadata
   - Initial Supply
3. Click "Create a token" to deploy your token
4. The token will be created and minted to your wallet address

## Technology Stack

- **Frontend**: React 18 with Vite
- **Blockchain**: Solana Web3.js
- **Token Standard**: SPL Token 2022
- **Wallet Integration**: Solana Wallet Adapter
- **Styling**: CSS with modern design

## 📁 Project Structure
```bash
solana-launchpad/
├── src/
│   ├── components/
│   │   └── TokenLaunchpad.jsx
│   ├── App.jsx
│   └── main.jsx
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

## Network

The application currently runs on **Solana Devnet**. Make sure your wallet is connected to devnet when creating tokens.

## Wallet Support

The following wallets are supported:
- Phantom
- Solflare
- Backpack
- Glow
- And more via Solana Wallet Adapter

## Learning Objectives

- Understanding Solana SPL token workflow
- Integrating wallets with frontend applications
- Building scalable Web3 user interfaces
- Handling blockchain transactions securely

## Learn More

- [Solana Documentation](https://docs.solana.com/)
- [SPL Token Documentation](https://spl.solana.com/token)
- [Solana Wallet Adapter](https://github.com/solana-labs/wallet-adapter)
