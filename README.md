### ETH + AVAX PROOF: Intermediate (Module-2)
## Project Overview
The “Function Frontend” project aims to demonstrate the interaction between a simple smart contract and a frontend application. The smart contract, named “Kitten,” includes several functions. The project focuses on displaying the values of these functions.

## Technologies Used

Solidity: A programming language for building smart contracts on the Ethereum blockchain.

Remix: An online Solidity IDE for development and testing.

HTML, CSS, and JavaScript: Front-end technologies for displaying contract data.

## Getting Started
# Executing Program
To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at Remix.

i) Create a New File: Once on the Remix website, create a new file by clicking on the “+” icon in the left-hand sidebar. Save the file with a .sol extension (e.g., frontendcode.sol). Copy and paste the code into the file.

ii) Compile the Code: Click on the “Solidity Compiler” tab in the left-hand sidebar. Make sure the “Compiler” option is set to “0.8.21” (or another compatible version), and then click on the “Compile frontendcode.sol” button.

iii) Deploy the Contract: Once the code is compiled, you can deploy the contract by clicking on the “Deploy & Run Transactions” tab in the left-hand sidebar. Select the “Kitten” contract from the dropdown menu, and then click on the “Deploy” button.

# Frontend Application
The frontend application interacts with the deployed “Kitten” smart contract to set, get, and increment a private value variable. The application showcases the values returned by the functions on the user interface.

# Project Structure
The project consists of the following files:

i) Frontendcode.sol: The contract allows users to set, get, and increment a private value variable.

ii) hardhat.config.js: The configuration file for Hardhat, a development environment for Ethereum software.

iii) package.json: The file is used to manage the dependencies and scripts for a project that utilizes Hardhat, a development environment for Ethereum software, along with a frontend built using Next.js and React.

# How to Run the Project
i) Deploy the “Kitten” Smart Contract: Deploy the contract on a local Ethereum network (like Hardhat Network).

ii) Configure Hardhat: Ensure your hardhat.config.js file is correctly set up for your development environment.

iii) Deploy the Frontend Application: Deploy the frontend application on a web server.

iv) Interact with the Frontend UI: Open your web browser and navigate to the URL where your frontend application is running.

## Conclusion
This contract demonstrates basic state management in Solidity, including setting, retrieving, and modifying a variable, as well as using assertions to enforce conditions.

## Authors

Ekta
## License

This project is licensed under the MIT License.

Feel free to reach out for any questions or further improvements to this project.
