# cibilscore

A decentralized application (dApp) that leverages blockchain technology to provide a transparent, secure, and verifiable way for users to check and manage their CIBIL scores. Built with a modern tech stack, this project demonstrates the integration of Web3 and traditional finance, solving the real-world problem of opaque credit scoring systems.



## Project Overview

### Problem Statement
- **Current Issue**: Traditional CIBIL scores lack transparency—users don’t know how often they’re updated, who updates them, or whether they’re accurate.
- **Solution**: A blockchain-based system where CIBIL scores are stored immutably, updated securely by financial institutions, and accessible to users via a simple interface with wallet-based authentication.

### Goals
- Provide users with real-time access to their credit scores.
- Ensure immutability and transparency using blockchain.
- Showcase skills in Web3 development, smart contracts, and frontend design.


## Features (MVP)
- **User Authentication**: Connect via MetaMask or WalletConnect for secure login.
- **CIBIL Score Check**: View your credit score stored on the blockchain.
- **Score Updates**: Financial institutions (admin) can update scores, recorded immutably.
- **Immutable Records**: All score data is stored on the Polygon Mumbai Testnet.
- **Simple UI**: A clean, intuitive interface built with React and Tailwind CSS.

### Future Enhancements (Post-MVP)
- AI-based credit score prediction.
- Loan eligibility checker.
- Real-time score update alerts.
- Decentralized Identity (DID) integration.
- CIBIL score dispute system.



## Tech Stack

### Frontend
- **React.js + TypeScript**: For a robust and type-safe user interface.
- **Tailwind CSS**: For rapid, responsive styling.
- **Web3.js / Ethers.js**: To interact with Ethereum-based blockchains.
- **MetaMask / WalletConnect**: For wallet integration and authentication.

### Backend
- **Solidity**: Smart contracts for score storage and updates.
- **Polygon Mumbai Testnet**: A scalable Ethereum Layer 2 solution for deployment.
- **Hardhat**: Development environment for compiling, testing, and deploying contracts.
- **Firebase (Firestore + Authentication)**: For user profile management.

### Tools & Libraries
- **Hardhat**: Smart contract development and testing.
- **Vercel / Netlify**: Frontend hosting (planned).
- **Pinata/IPFS**: Optional for decentralized file storage (future).
- **Chainlink Oracles**: Optional for real-world data integration (future).


## Project Setup

### Prerequisites
- **Node.js**: v16 or later.
- **MetaMask**: Installed in your browser with a Polygon Mumbai account.
- **Polygon Mumbai Faucet**: Get test MATIC from [Mumbai Faucet](https://mumbaifaucet.com/).
- **Git**: For version control.

### Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/vigneshkriishna/cibilscore.git
   cd cibilscore
