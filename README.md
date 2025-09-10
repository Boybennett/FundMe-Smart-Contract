FundMe Smart Contract 💰
This project is a decentralized application (DApp) that allows users to send funds to a smart contract on the Ethereum blockchain. It serves as an educational tool to demonstrate the fundamental concepts of smart contract development, including:

Receiving Ether: Implementing a payable function to accept cryptocurrency from users.

Managing State Variables: Storing and updating a list of funders and the total amount of funds received.

Controlling Access: Using modifiers to restrict functions to only the contract owner.

Withdrawal Logic: Creating a function to allow the contract owner to withdraw all accumulated funds.

The project is built with Solidity, the primary language for writing Ethereum smart contracts.

Key Components
FundMe.sol: This is the main smart contract file. It contains the logic for sending funds, tracking funders, and handling withdrawals.

PriceConverter.sol: This is a library contract used by FundMe.sol to get the current price of ETH in USD, ensuring that the minimum contribution is met.

How to Use
Prerequisites
Node.js: Link to Node.js download page

Git: Link to Git download page

Foundry: Link to Foundry installation instructions

Installation
Clone the repository:

Bash

git clone https://github.com/Boybennett/FundMe-Smart-Contract.git
cd FundMe-Smart-Contract
Install dependencies:

Bash

forge install
Testing
To run the tests for the smart contract, use the following command:

Bash

forge test
Contact
For any questions or suggestions, feel free to open an issue or contact the repository owner.

License
This project is licensed under the MIT License. See the LICENSE.txt file for details. 
