# chetan_token - Simple Token Contract

## Description

This Solidity contract, named "chetan_token," is a simple implementation of a custom token on the Ethereum blockchain. The contract supports token minting and burning functionality. It uses the ERC-20-like standard for basic token behavior, allowing transfers and balance tracking for token holders.

## Token Details

- Token Name: CHETAN
- Token Abbreviation: CTN
- Total Supply: 0 (initially)

## Contract Functions

### mint

The `mint` function allows the contract owner (deployer) to create new tokens and assign them to a specific address. This function increases the total token supply and updates the balance of the target address.

#### Parameters

- `address _address`: The address to which the new tokens will be assigned.
- `uint _value`: The number of tokens to mint and assign to the specified address.

### burn

The `burn` function allows token holders to destroy their tokens, effectively reducing the total supply and updating the balance of the token holder.

#### Parameters

- `address _address`: The address of the token holder who wants to burn their tokens.
- `uint _value`: The number of tokens to burn.

## Getting Started

### Executing the Contract

To run this contract, you can use Remix, an online Solidity IDE. Follow the steps below to interact with the contract:

1. Go to the Remix website at [https://remix.ethereum.org/](https://remix.ethereum.org/).
2. Create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., chetan_token.sol).
3. Copy and paste the provided code into the file.
4. To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.18" (or another compatible version), and then click on the "Compile chetan_token.sol" button.

### Deploying and Interacting with the Contract

1. Click on the "Deploy & Run Transactions" tab in the left-hand sidebar.
2. Select the "chetan_token" contract from the dropdown menu.
3. Click on the "Deploy" button to deploy the contract to the Ethereum blockchain.
4. Once the contract is deployed, you can interact with it by calling the `mint` and `burn` functions.
5. To mint new tokens, click on the "chetan_token" contract in the left-hand sidebar, enter the address and the number of tokens to mint, and then click on the "transact" button to execute the function.
6. To burn tokens, follow the same process as minting but use the `burn` function instead.

## Authors

Metacrafter Chetan

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
