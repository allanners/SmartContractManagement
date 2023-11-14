# Smart Contract Management

This project contains the program for the submission of the assessment Smart Contract Management.

## Description

The goal of the project is to connect the program to MetaMask and manipulate the front-end using different functionalities. In the program, I have modified the deposit() and withdraw() methods and added a method called setTransacCount(). In this method, I manipulated a variable called transactionHistory and pushed all transactions in this variable. I also added a button that checks the signer once clicked.

## Getting Started

### Executing program

In order to run this program, it is recommended to clone the whole repository and perform the necessary set up in order to avoid errors. After cloning the github, you will want to do the following to get the code running on your computer.

1. Inside the project directory, in the terminal type: npm i
2. Open two additional terminals in your VS code
3. In the second terminal type: npx hardhat node
4. In the third terminal, type: npx hardhat run --network localhost scripts/deploy.js
5. Back in the first terminal, type npm run dev to launch the front-end.

After this, the project will be running on your localhost. Typically at http://localhost:3000/

## Submitted by:

- Allan C. Magtibay Jr.
- 202011500@fit.edu.ph
