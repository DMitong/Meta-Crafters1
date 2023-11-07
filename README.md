# MyToken Smart Contract

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

The `MyToken` smart contract is a simple example of an Ethereum-based token with basic functionalities to mint and burn tokens. It is designed for educational purposes and can be used as a starting point for creating your own token contracts.

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
- [Contract Details](#contract-details)
- [Functions](#functions)

## Overview

The `MyToken` contract provides a minimalistic ERC-20-like token implementation with the following features:

- Token name: "MITONG TOKEN"
- Token abbreviation: "MGT"
- Total supply management
- Minting tokens
- Burning tokens

## Getting Started

To deploy and interact with the `MyToken` contract, you can follow these steps:

1. **Clone the Repository**: Clone this repository to your local environment.

2. **Compile and Deploy**: Compile the contract using a Solidity compiler and deploy it to an Ethereum network of your choice. You can use development tools like Remix.

## Contract Details

- **Solidity Version**: 0.8.18
- **License**: MIT

## Functions

### Mint Function

- **Description**: Mint new tokens and add them to the total supply and the minter's address balance.
- **Parameters**:
  - `_address` (data type: address): The address of the account minting the tokens.
  - `_value` (data type: uint): The number of tokens to mint.
- **Visibility**: Public

### Burn Function

- **Description**: Burn a specific number of tokens from the sender's balance, reducing the total supply.
- **Parameters**:
- `_address` (data type: address): The address of the account burning the tokens.
- `_value` (data type: uint): The number of tokens to burn.
- **Visibility**: Public
