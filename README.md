# Project Title

Getting Started with Solidity

## Description

"Getting Started with Solidity" introduces developers to the fundamentals of Solidity, the primary programming language for writing smart contracts on the Ethereum blockchain. This guide covers basic syntax, key concepts, and essential tools needed to begin developing secure and efficient decentralized applications (dApps).

## Getting Started

### Installing

1. Install Node.js and npm: Download and install Node.js from [nodejs.org](https://nodejs.org), which includes npm. Verify the installation by running `node -v` and `npm -v` in your terminal.

2. Install Truffle: Use npm to install Truffle, a popular development framework for Ethereum. Run `npm install -g truffle` in your terminal.

3. Install Solidity Compiler: Use npm to install the Solidity compiler by running `npm install -g solc` in your terminal. This compiler is essential for writing and compiling smart contracts.
### Executing program

1. Initialize a Truffle Project: In your terminal, create a new directory for your project and navigate into it. Run `truffle init` to set up the project.

2. Write a Smart Contract: In the `contracts` directory, create `HelloWorld.sol` with the following content:
   ```solidity
   // SPDX-License-Identifier: MIT
   pragma solidity ^0.8.0;

   contract HelloWorld {
       string public greet = "Hello, World!";
   }
   ```

3. Compile and Deploy: Run `truffle compile` to compile the contract, then `truffle migrate` to deploy it to a local blockchain like Ganache.


## Authors
Himanshu Rajoria

ex. [@himanshu0069](himanshu.rajoria2003@gmail.com)



## License

This project is licensed under the MIT License.