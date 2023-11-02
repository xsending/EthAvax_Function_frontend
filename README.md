# EthAvax_Function_frontend

This program is a localhost website program through the combination of Javascript and Solidity where the JS code serves as the website frontend script, while the Solidity code serves as the backend for Ethereum transactions. The purpose of this program is to demonstrate how the JS frontend communicates with the Solidity backend in order to perform smart contract transactions.

## Description

This program simulates an ATM where you can withdraw and deposit your currency based on the amount specified by the user. It uses Javascript as frontend which the user can interact with, and it communicates the user's action on the frontend to Solidity on the backend in order to perform the transaction the user requires. This program uses the hardhat node to ensure that no real cryptocurrency is being used and lost during the program's running duration. This program serves as a good example in demonstrating how JS communicates with Solidity to perform smart contract transactions through a website.

## Getting Started

### Executing program
To run this program, you can clone this repository into your local machine, or you can use Gitpod (https://www.gitpod.io) to run the program online. Once you're done cloning, you can set up the localhost website by following these steps:
1. Inside the project directory, in the terminal type: npm i
2. Open two additional terminals in your VS code or Gitpod
3. In the second terminal type: npx hardhat node
4. In the third terminal, type: npx hardhat run --network localhost scripts/deploy.js
5. Back in the first terminal, type npm run dev to launch the front-end.

After this, the project will be running on your localhost. Typically at http://localhost:3000/

Make sure to check whether your port 8545 is made public, and make sure to also set up your MetaMask by adding your localhost network as a custom network within MetaMask.

## Authors

Abel Gomez  

## License

This project is licensed under the MIT License - see the LICENSE.md file for details
