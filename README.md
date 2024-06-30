# Frontend-Meta
This document showcases how to create a simple Solidity smart contract with functions and interact with it from a basic frontend to display the values.
## Technologies Used
-Solidity: A programming language for building smart contracts on the Ethereum blockchain.
-Remix: An online Solidity IDE for development and testing.
-HTML, CSS, and JavaScript: Front-end technologies for displaying contract data.

## Getting Started
## Executing program
To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., HelloWorld.sol). Copy and paste the following code into the file:

    // SPDX-License-Identifier: MIT
    pragma solidity ^0.8.21;

    contract kitten {
        uint256 private value;

    // Function to set the value
    function setValue(uint256 _value) public {
        value = _value;
    }

    // Function to get the value
    function getValue() public view returns (uint256) {
        return value;
    }

    // Function to increment the value
    function incrementValue() public {
        value += 1;
    }
    } uint public num;
       function errorAssert() public view {  assert(num == 0);  }}

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.18" (or another compatible version), and then click on the "Compile frontend.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "Kitten" contract from the dropdown menu, and then click on the "Deploy" button.

 
## License
This project is licensed under the MIT License.

Feel free to reach out for any questions or further improvements to this project.
