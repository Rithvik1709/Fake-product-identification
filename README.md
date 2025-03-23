# Fake Product Identification using Blockchain Technology

## Introduction
Fake and counterfeit products pose a significant challenge to consumers and businesses worldwide. This project leverages blockchain technology to ensure product authenticity and prevent counterfeiting. By storing product details on a decentralized blockchain network, customers and businesses can verify the legitimacy of a product before purchasing.

## Features
- **Decentralized Product Verification:** Product details are stored on a secure blockchain ledger.
- **Unique Product Identity:** Each product is assigned a unique hash or QR code for verification.
- **Tamper-Proof Records:** Information on the blockchain cannot be altered or deleted.
- **Transparency and Trust:** Consumers and businesses can verify product authenticity.
- **Smart Contracts:** Automate verification processes and transactions.
- **User-Friendly Interface:** A web-based or mobile application for product scanning and validation.

## Technology Stack
- **Blockchain Platform:** Ethereum 
- **Smart Contracts:** Solidity 
- **Frontend:** HTML,CSS,JS
- **Backend:** Flask 
- **QR Code Generation:** Python 
- **Authentication:**  MetaMask integration

## How It Works
1. **Manufacturer Registration:** Manufacturers register on the platform and add product details to the blockchain.
2. **Product Tagging:** A unique hash (QR code or RFID) is generated and linked to the blockchain entry.
3. **Customer Verification:** Customers scan the QR code via the web or mobile app to retrieve product authenticity data.
4. **Blockchain Validation:** The system checks the blockchain for matching records and displays authenticity status.
5. **Alerts & Reporting:** Customers can report counterfeit products, helping authorities take action.

## Installation
### Prerequisites
- Node.js & npm
- Python (for backend processing, if needed)
- Ganache (for Ethereum blockchain testing)
- MetaMask (for Ethereum-based transactions)
- IPFS (for decentralized storage)

### Steps to Run Locally
1. **Clone the Repository**
   
2. **Install Dependencies**
   ```bash
   npm install
   ```
3. **Start Blockchain (Ganache for local Ethereum network)**
   ```bash
   ganache-cli
   ```
4. **Deploy Smart Contracts**
   ```bash
   truffle migrate --network development
   ```
5. **Run the Backend Server**
   ```bash
   npm run server
   ```
6. **Run the Frontend Application**
   ```bash
   npm start
   ```
