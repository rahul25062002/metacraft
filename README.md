# MyToken - Simple Ethereum Token Contract

MyToken is a basic Ethereum smart contract that represents a simple token. This contract allows you to mint (create) and burn (destroy) tokens. It includes basic functionality to manage token balances for different addresses.

## Contract Details

- **Name:** MyToken
- **Token Name:** Rahul
- **Token Symbol:** rahulToken

## Features

The MyToken contract includes the following features:

1. **Minting Tokens**: You can mint (create) tokens and assign them to a specific Ethereum address. The total supply of tokens is increased, and the balance of the address is updated accordingly.

2. **Burning Tokens**: You can burn (destroy) tokens held by a specific Ethereum address. The total supply of tokens is decreased, and the balance of the address is reduced accordingly.

## Smart Contract Functions

The contract includes the following functions:

- `mint(address _address, uint _value)`: This function allows you to mint a specified number of tokens and assign them to a given Ethereum address. The function increases the total token supply and updates the balance of the address.

- `burn(address _address, uint _value)`: This function allows you to burn a specified number of tokens held by a given Ethereum address. The function reduces the total token supply and decreases the balance of the address. It performs a check to ensure that the address has enough tokens to burn before proceeding.
