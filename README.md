# Create a Token
MyToken is a simple token contract designed to demonstrate the fundamentals of Solidity, the programming language for Ethereum smart contracts. This project serves as a learning tool for new programmers to gain hands-on experience with Solidity and blockchain development concepts like minting, burning, and managing token balances. By working with this contract, developers can enhance their understanding of basic smart contract structures and functions.

## Description
MyToken is a simple program for beginners to learn Solidity and blockchain development. It covers key concepts such as minting (creating tokens), burning (destroying tokens), and managing balances through mappings. This project provides a straightforward introduction to smart contract basics, helping developers understand how token contracts work on the Ethereum blockchain.

## Getting Started
### Executing program
To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/. 

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., myToken.sol). Copy and paste the code to the file.

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.26" (or another compatible version), and then click on the "Compile myToken.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "MyToken" contract from the dropdown menu, and then click on the "Deploy" button.

Once deployed, you can interact with the contract. To view the token name and abbreviation, click on tokenName and tokenAbbrv. 

To mint tokens, use the dropdown beside the mint button. In the "Deploy & Run Transactions" tab, scroll up to the "Account" section, copy the account address, and input it into the mint function's address field. Then, specify the number of tokens you want to mint and click "transact." You can verify that the tokens were successfully minted by checking the totalSupply, which should reflect the number of tokens you minted. To check balances, input the account address. 

To burn tokens, input the address and the number of tokens you wish to burn. Make sure the value you want to burn doesn't exceed the current balance, or the transaction will fail.

## Authors
Ana Mary Colin A. Rasonable
