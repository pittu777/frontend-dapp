# Ethereum Smart Contract Interaction Web Application

This project demonstrates how to interact with a smart contract on the Ethereum blockchain using a web application built with React. Users can deposit Ether into the contract and update a greeting message stored on the blockchain. The web application provides a user-friendly interface to perform these actions and displays the current contract balance and greeting message. This project serves as a practical example for developers learning about blockchain integration with web applications.

## Description
This project is a simple web application built with React that interacts with a smart contract deployed on the Ethereum blockchain. The smart contract, written in Solidity, allows users to deposit Ether and set a greeting message, which is stored on the blockchain. The web application displays the current greeting and the contract balance in Ether, providing a seamless interface for users to interact with the blockchain.

## Getting Started
### Prerequisites

Before you begin, ensure you have the following installed:

Node.js (version 14.x or higher)
npm
Metamask (browser extension)
Hardhat

Installing
Clone the repository:


git clone https://github.com/yourusername/your-repo.git
cd your-repo
Install dependencies for the client:


cd client
npm install
Install dependencies for the contract:


cd contract
npm install
Configuration
Ensure you have the correct configuration for the Hardhat network in hardhat.config.js. Here is an example configuration:


module.exports = {
  solidity: "0.8.4",
  networks: {
    localhost: {
      url: "http://127.0.0.1:8545"
    }
  }
};

## Executing Program

Running the Hardhat Local Blockchain
Start the local Hardhat node:
- [Node.js](https://nodejs.org/) (version 14.x or higher)

