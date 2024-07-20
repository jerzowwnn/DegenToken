# DegenToken Project

This repository contains the files for my Module 4 project of the ETH + AVAX PROOF: Intermediate EVM Course. 

## Description

This project concerns a smart contract that creates an ERC20 token named Degen (DGN) for Degen Gaming. It is deployed on the Avalanche network and offers the following functionalities:
- createTokens() = allows the owner to mint tokens in their wallet. It accepts the contract owner's address and amount to be minted.
- transferTokens() = allows the user to transfer tokens to a specified address. It takes the receipient's address and amount to be transferred. Note that the amount to be transferred must be greater than or equal to the account's balance.
- redeemItem() = allows the user to redeem an item from the in-game store. It takes the item ID as input. Note that the account must have a balance sufficient to pay or redeem the item.
- verifyBalance() = allows the user to check their current balance. It takes the account's address as input.
- destroyTokens() = allows the user to burn tokens from their account. It takes the  amount to be burned as input. Note that the amount to be burned must be greater than or equal to the account's balance.
- getItem() = allows the user to view the details of an item. It takes the item's ID as input.
- displayItems() = allows the user to view all items in the in-game store.

## Pre-requisites
To run this project smoothly, it is advised to have the following:
- Metamask Account with Available balance
- Remix IDE and Solidity Compiler
- Node.js

### Executing program

# Setting up the Project
1. Clone this repository in your local device. You may use this via software tools such as Github desktop or your terminal.
2. Open a terminal in the project's root directory.
3. Execute `npm install` in the terminal and wait until the installation is complete.
4. In the same terminal, run `remixd`.
5. Open your web browser and navigate to Remix IDE.
6. On Remix, select the File Explorer Tab.
7. Under Workspaces, select "connect to localhost" and click "Connect."

# Deploying the Project
1. Navigate to Remix IDE.
2. Go to the Solidity Compiler tab and select "Compile DegenToken.sol"
3. Go to the Deploy and Run Transactions tab.
4. Under "Environment," choose "Injected Provider - MetaMask."
5. Verify that Metamask is connected to the Avalanche Fuji Testnet.
6. Deploy the contract via the "Deploy" button.

### Help
Should any issues arise, please refer to the official ERC20 Documentation and Remix IDE guides for additional guidance.


## Authors

Jerson Gabriel D. Dizon, Mapua University
jgddizon@mymail.mapua.edu.ph
