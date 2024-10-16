# Technical Specification

## Introduction
I will present more in detail each functionality of my token in ERC-20 standard.

## Features of ERC-20 Token
- **Transfer** : Allows token holders to transfer tokens to another account.
- **Approve** : Enables a spender to withdraw up to an approved amount.
- **TransferFrom** : Allows a spender to transfer tokens on behalf of the token owner.
- **BalanceOf** : Returns the token balance of a specific account.
- **Allowance** : Returns the remaining number of tokens that a spender is allowed to spend from an owner's account.
- **Burn** : Allows token holders to burn their tokens.
- **BurnFrom** : Allows the burn of specific token holder by the contract owner.
- **Mint** : Allows contract owner to mint new tokens (here the multisig of  2/2).
- **TransferOwnership** : Allows contract owner to transfer the ownership of the contract.

## Events of ERC-20 Token
- **Transfer** : Emitted when value tokens are moved from one account (from) to another (to).
- **Approval** : Emitted when the allowance of a spender for an owner is set by a call to approve. value is the new allowance.

## Conclusion
This ERC-20 standard is created to balance flexibility, security and compliance. It supports a wide range of use cases within the Ethereum ecosystem.