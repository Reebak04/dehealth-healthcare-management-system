# dehealth-healthcare-management-system

## Description
Decentralized Image Upload and Sharing facilitates secure and decentralized image storage and sharing on the blockchain. Utilizing Solidity for smart contract functionality and React for the front-end interface, this project enables users to upload images to IPFS and manage access through blockchain-powered controls.

---

## About
This project provides a decentralized alternative to traditional cloud storage platforms, ensuring secure, immutable, and user-controlled access to images. By leveraging the Ethereum blockchain and IPFS, it addresses concerns about centralized storage vulnerabilities and lack of user ownership. Users can upload images, share access with specific individuals, and revoke access seamlessly through a React-based interface.

---

## Features
- *Decentralized Storage*: Images are stored on IPFS, ensuring data integrity and tamper-proof storage.
- *Smart Contract Access Control*: Manage ownership and sharing of images using Solidity-based smart contracts.
- *User-Friendly Interface*: A React front-end for easy image upload and access management.
- *Secure Sharing*: Grant or revoke access permissions through blockchain transactions.

---

## Requirements
- *Operating System*: Compatible with Windows 10, macOS, and Linux.
- *Development Tools*:
  - Node.js (version 14 or later)
  - Hardhat (for Ethereum development)
  - Metamask browser extension
- *Blockchain and Storage*:
  - Ethereum testnet (e.g., Rinkeby, Goerli) or local Ethereum network
  - Pinata API for IPFS integration
- *Libraries and Frameworks*:
  - Solidity for smart contracts
  - React.js for the user interface
  - IPFS for decentralized file storage

---

## Installation


### Install Dependencies
#### Backend (Hardhat):
bash
cd Dgdrive3.0
npm install

#### Frontend (React):
bash
cd client
npm install


### Compile and Deploy Smart Contract
#### Compile:
bash
npx hardhat compile

#### Deploy:
bash
npx hardhat run scripts/deploy.js --network <network-name>


### Start the React Application
bash
npm start


---

## Configuration
- *Metamask*: Install and configure Metamask for Ethereum interactions.
- *Contract Address*: Update the deployed contract address in the App.js file in the React application.
- *Pinata API Keys*: Add your Pinata API keys in the FileUpload.js file for IPFS integration.

---

## Usage
1. *Upload Images*:
   - Log in with Metamask.
   - Upload an image through the React interface. The image will be stored on IPFS, and its metadata will be recorded on the blockchain.

2. *Access Images*:
   - Use the "Get Data" feature to retrieve images uploaded by other users (access permissions required).

3. *Manage Access*:
   - Grant or revoke access to your uploaded images using the smart contract functionality.

---

## System Architecture
The project integrates multiple components:
- *Frontend*: React.js for UI/UX.
- *Backend*: Hardhat for Ethereum development.
- *Storage*: IPFS via Pinata for decentralized storage.
- *Smart Contracts*: Solidity for ownership and access management.

(Include a system architecture diagram here if available)

---

## Output

![WhatsApp Image 2024-12-29 at 15 38 04_f26796d9](https://github.com/user-attachments/assets/0632d00c-2983-4a19-830b-bebe56bdc9d1)

![WhatsApp Image 2024-12-29 at 15 35 47_cf5b6638](https://github.com/user-attachments/assets/2aee1093-bba1-47ba-859b-c7f231416fa0)

![WhatsApp Image 2024-12-29 at 15 38 04_32fe017d](https://github.com/user-attachments/assets/0f928621-2ba7-4cdd-a312-2bbcdca652be)

![WhatsApp Image 2024-12-29 at 15 38 04_e0fa1a66](https://github.com/user-attachments/assets/d8f61120-75b2-4105-bf53-482dcd29eb08)


---

## Results and Impact
- *Enhanced Security*: Eliminates single points of failure by decentralizing storage.
- *User Ownership*: Empowers users with complete control over their data.
- *Immutable Storage*: Ensures that images cannot be altered or deleted maliciously.

This project demonstrates the practical application of blockchain technology in decentralized storage solutions, paving the way for more secure and user-centric platforms.

---

## Future Enhancements
- Support for additional file types beyond images.
- Integration with more blockchain networks.
- Improved UI/UX for non-technical users.
- Advanced sharing options, such as time-bound access or group sharing.

---
