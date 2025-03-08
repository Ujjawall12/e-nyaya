**E-nyaya - Blockchain-Based Secure Vault (Vite Project)**

E-nyaya is a decentralized, secure vault application built on the Vite blockchain. It allows users to store and manage sensitive data securely using blockchain technology, ensuring immutability, transparency, and enhanced security and also handles legal court cases details.


**Snapshots of project:**

![Alt text](project-assets/Screenshot%202025-03-09%20020518.png)
![Alt text](project-assets/Screenshot%202025-03-09%20020540.png)
![Alt text](project-assets/Screenshot%202025-03-09%20020718.png)
![Alt text](project-assets/Screenshot%202025-03-09%20020742.png)

**E-Vault Features :**
Registering new clients, lawyers, judges on Evault
Registering legal case betwwen 2 clients with their respectice clients
Automatic / Random allocation of judges to registered cases
Login system for clients, lawyers & judges using Aadhar UID
Updating case progress by allocated judges & lawyers
Uploading case documents to IPFS & keeping case records by associated case lawyers
Fetching basic case information using caseIDs by general public and police
Metamask wallet integration and usage for access authorization


**Tech Stack :**


# Frontend :

Vite JS
Tailwind CSS
React Toastify
React Charts
Shadcn UI


# Backend :

Node JS
Hardhat Toolkit
Metamask Wallet
Ethers JS
Alchemy
Pinata IPFS


# Deployed Chains :

Ethereum Sepolia Testnet
Polygon Amoy Testnet
Hardhat Local Testnet 
Morph Testnet 


**Guide for Testing on Local Hardhat Network**
-->This guide will help you set up and test the project on a local Hardhat network. Follow the steps below to 
   configure the environment, deploy smart contracts, and run the frontend.


# Step 1: Set Up Environment Variables

-->Navigate to the blockchain-hardhat folder.
-->Create a new .env file by using the .env.example file as a reference. Copy the structure and fill in the required
 values.

# Step 2: Backend Setup

## Terminal 1: Start Local Hardhat Node
1.Move into the blockchain-hardhat folder.
2.Install the required dependencies (only needed once).
3.Start the local Hardhat node. This will run a local Ethereum network and display a list of accounts with their private keys.

## Terminal 2: Deploy Smart Contracts
1.In a new terminal, navigate to the blockchain-hardhat folder (if not already there).
2.(Optional) Run tests to ensure everything is working correctly.
3.Deploy the smart contract to the local Hardhat network. After deployment, note the contract address displayed in the terminal.
4.(Optional - For Sepolia Testnet) Deploy the smart contract to the Sepolia network. Note the contract address for Sepolia as well.
5.Update the backend-config.json file inside the frontend-vite folder:
-->For localhost (chain ID 31337), update the address field under 31337 with the contract address from Terminal 2.
-->(Optional) For Sepolia (chain ID 11155111), update the address field under 11155111.

# Step 3: Frontend Setup

## Terminal 1: Start the Frontend
1.Navigate to the frontend-vite folder.
2.Install the required dependencies (only needed once).
3.Start the frontend development server. The frontend will be accessible at http://localhost:5173.


## Important Notes
1.Ensure the .env file is properly configured with the required keys.
2.Update the backend-config.json file with the correct contract addresses after deployment.
3.Use the local Hardhat network for testing and development. For production-like testing, deploy to Sepolia or another testnet.


# Folder-directory-overview 
e-nyaya/
│── frontend-vite/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── blockchain-api/
│   │   ├── components/
│   │   │   ├── ui/
│   │   │   │   ├── AdminDashboardComponent.jsx
│   │   │   │   ├── CaseDetailsComponent.jsx
│   │   │   │   ├── Footer.jsx
│   │   │   │   ├── HeroSection.jsx
│   │   │   │   ├── Loader.jsx
│   │   │   │   ├── LoginComponent.jsx
│   │   │   │   ├── Navbar.jsx
│   │   │   │   ├── ProjectStatistics.jsx
│   │   │   │   ├── RegisterANewCaseComponent.jsx
│   │   │   │   ├── SearchCaseDetailsComponent.jsx
│   │   │   │   ├── SignUpComponent.jsx
│   │   ├── lib/
│   │   │   ├── utils.js
│   │   ├── pages/
│   │   │   ├── AdminPage.jsx
│   │   │   ├── CaseDetailsPage.jsx
│   │   │   ├── GetCaseDetailsPage.jsx
│   │   │   ├── HomePage.jsx
│   │   │   ├── LoginPage.jsx
│   │   │   ├── RegisterNewLegalCasePage.jsx
│   │   │   ├── SignUpPage.jsx
│   │   │   ├── TestPage.jsx
│   ├── App.css
│   ├── App.jsx
│   ├── backend-config.json
│   ├── index.css
│   ├── main.jsx
│   ├── .env.example
│   ├── .eslintrc.cjs
│   ├── .gitignore
│   ├── components.json
│   ├── index.html
│   ├── jsconfig.json
│   ├── package.json
│   ├── postcss.config.js
│   ├── tailwind.config.js
│   ├── vite.config.js


# Made at ELectrothon 7.0 by TEAM SCAM 2K25
## Team member details: 
Ananya Pratap singh -- 
Ujjawal Maheshwari  --  https://github.com/Ujjawall12
Pratyush 
Archisman