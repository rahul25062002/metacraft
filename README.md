# metacraft

Custom Token Contract
This Solidity smart contract implements a custom token called "Rahul" with the symbol "Rahultoken". Initially, the total supply is set to 0.

Functions
Mint
The mint function allows the owner to create new tokens and assign them to a specific address.

Parameters
address _address: The recipient's address.
uint _value: The amount of tokens to mint.
Burn
The burn function enables the owner to remove existing tokens from a specific address.

Parameters
address _address: The address from which the tokens will be burned.
uint _value: The amount of tokens to burn.
Usage
Deploy the contract on a compatible Ethereum Virtual Machine (EVM).
Use a compatible interface like Remix or Truffle to interact with the contract.
Call the mint function to create new tokens.
Call the burn function to destroy existing tokens.
