# Stella Token
- It's a token contract build using soroban SDK
# Soroban Token Contract

This contract provides a sample implementation of the Soroban token interface. It is designed to be used within the Soroban blockchain ecosystem.

## Overview

The Soroban token contract allows for the creation, management, and transfer of tokens within the Soroban blockchain. It includes functionalities such as token minting, transferring, allowance management, burning, and metadata retrieval.

## Getting Started

To use this contract, follow these steps:

1. **Initialization**: Initialize the contract with the desired parameters such as the administrator's address, decimal, name, and symbol of the token.

2. **Minting Tokens**: Mint new tokens to a specified address. Only the administrator can mint tokens.

3. **Token Transfer**: Transfer tokens between addresses.

4. **Allowance Management**: Approve spending allowances for specific addresses and manage them accordingly.

5. **Token Burning**: Burn tokens to remove them from circulation.

## Usage

### Initialization

To initialize the token contract, call the `initialize` function with the following parameters:

- `admin`: Address of the administrator.
- `decimal`: Number of decimal places for the token.
- `name`: Name of the token.
- `symbol`: Symbol of the token.

### Minting Tokens

To mint new tokens, call the `mint` function with the following parameters:

- `to`: Address to receive the minted tokens.
- `amount`: Amount of tokens to mint.

### Token Transfer

To transfer tokens between addresses, call the `transfer` function with the following parameters:

- `from`: Address transferring the tokens.
- `to`: Address receiving the tokens.
- `amount`: Amount of tokens to transfer.

### Allowance Management

To approve spending allowances for specific addresses, call the `approve` function with the following parameters:

- `from`: Address granting the allowance.
- `spender`: Address to which the allowance is granted.
- `amount`: Amount of tokens to allow spending.
- `expiration_ledger`: Expiration ledger for the allowance.

### Token Burning

To burn tokens, call the `burn` function with the following parameters:

- `from`: Address from which the tokens are burned.
- `amount`: Amount of tokens to burn.

## Additional Information

For more information on the Soroban blockchain and its ecosystem, refer to the official documentation and resources provided by the Soroban team.

