# Tokenizer
## Introduction
I will present my token and why i chose every technology or design pattern for my token.

## Blockchain
- **[Ethereum](https://ethereum.org/en/)**: I chose Ethereum as blockchain for my token because 
it's the most used blockchain for token creation, and also because it's stable and secure crypto ecosystem.

## Creation of my token
- **Solidity with [OpenZeppelin](https://wizard.openzeppelin.com)**: He helps me create the smart contract with all common functions.
- **Sepolia Testnet**: It's one testnet of Ethereum so i can use test eth to deploy and interact with my token contract without spending real eth.
- **[Metamask](https://metamask.io/)**: I use Metamask to have an Ethereum wallet. It gives me the ability to interact with the Ethereum blockchain by signing transactions through the app.

## Token features
- **Burnable**: Allow token holders to burn their tokens.
- **Mintable**: Allow token owner to mint new tokens.
- **ERC-20** I chose the ERC-20 standard because it's the most appropriate for token creation on Ethereum.  
It's also compatible with most of the wallets, exchanges and smart contracts.

## Deployment
- **[Remix](https://remix.ethereum.org/)**: The IDE Remix compile my smart contract, and deploy it with this ether.js library.

## Security
- **Ownable Contract**: I chose to restrict some functionalities like minting only by the contract owner.
- **[Multi signature with Safe Smart Contract](https://app.safe.global)** : To interract the contract, i need to have the approval of the multi-sig address which is created by Safe Smart Contract.  
It offers a secure way to interact with the blockchain because it requires the approval of multiple accounts.

## Address of the token
- **[Etherscan](https://sepolia.etherscan.io/token/0xb5143adfb361c99cee17e474406fad189e28b56b?a=0x2cafb098f01d9199c04481cc3875c3acf4bf8da0)**: You can use this website to see the contract of my token after deployment and all the transactions. As well, this is [my address](https://sepolia.etherscan.io/address/0x2cafb098f01d9199c04481cc3875c3acf4bf8da0) on etherscan.
