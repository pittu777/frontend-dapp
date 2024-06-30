React DApp
This is a decentralized application (DApp) built with React and Ethers.js, allowing users to interact with an Ethereum smart contract.

Features
View Greeting: Displays the current greeting message from the smart contract.
Deposit ETH: Allows users to deposit ETH into the contract.
Change Greeting: Users can update the greeting message stored in the contract.
Prerequisites
Node.js and npm installed
MetaMask or a similar Ethereum wallet browser extension
An Ethereum test network (e.g., Hardhat)
Setup




Install dependencies:


npm install
Start the development server:


npm start
Connect MetaMask: Ensure your MetaMask is connected to the same network as your local blockchain (e.g., Hardhat or Ganache).

Usage
View Greeting: The app displays the current greeting message on load.

Deposit ETH:

Enter an amount in ETH to deposit.
Click "Deposit" to send the transaction.
Change Greeting:

Enter a new greeting message.
Click "Change" to update the greeting in the contract.
Smart Contract
The application interacts with a smart contract deployed at the address 0x5FbDB2315678afecb367f032d93F642f64180aa3. Ensure this contract is deployed on your local blockchain before using the app.
