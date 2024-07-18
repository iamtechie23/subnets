# ERC20 and Vault Smart Contracts - README

## Introduction

This repository contains two key smart contracts:
1. **ERC20 Token Contract**: Implements a standard ERC20 token with basic functionalities.
2. **Vault Contract**: A smart contract that allows users to deposit ERC20 tokens and withdraw them later, offering basic vault functionalities.

## Prerequisites


## ERC20 Token Contract

### Overview

The ERC20 token contract is a standard implementation of the ERC20 interface, providing basic functionalities such as minting, transferring, and querying balances and allowances.

### Key Functions

- `name()`: Returns the name of the token.
- `symbol()`: Returns the symbol of the token.
- `decimals()`: Returns the number of decimals the token uses.
- `totalSupply()`: Returns the total supply of the token.
- `balanceOf(address account)`: Returns the balance of the specified address.
- `transfer(address recipient, uint256 amount)`: Transfers `amount` tokens to `recipient`.
- `approve(address spender, uint256 amount)`: Approves `spender` to spend `amount` tokens on behalf of the caller.
- `transferFrom(address sender, address recipient, uint256 amount)`: Transfers `amount` tokens from `sender` to `recipient`.
- `allowance(address owner, address spender)`: Returns the remaining number of tokens that `spender` is allowed to spend on behalf of `owner`.

## Vault Contract

### Overview

The Vault contract allows users to deposit ERC20 tokens and withdraw them later. It keeps track of user balances and provides mechanisms for deposits and withdrawals.

### Key Functions

- `deposit(uint256 amount)`: Deposits `amount` tokens into the vault.
- `withdraw(uint256 amount)`: Withdraws `amount` tokens from the vault.
- `balanceOf(address account)`: Returns the balance of the specified address in the vault.


## Contact

For any questions or suggestions, please contact [Your Name] at [your.email@example.com].
