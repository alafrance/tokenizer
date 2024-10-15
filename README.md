# Tokenizer
## Introduction
I will present my token and why i choose every technology or design pattern for my token.

## Blockchain
- **[Ethereum](https://ethereum.org/en/)**: I choose Ethereum as blockchain for my token because 
it's the most used blockchain for token creation, and also because it's stable and secure crypto ecosystem.

## Creation of my token
- **Solidity with [OpenZeppelin](https://wizard.openzeppelin.com)**: He helps me to create the smart contract of the token rules
- **Sepolia Testnet**: It's the default testnet of Ethereum so i can use fake ether to deploy my token and test it without spending real money.
- **[Metamask](https://metamask.io/)**: And i use Metamask to have a Ethereum wallet that contains my sepolia ETH and give me the ability to deploy and be the owner of my token with the private key of my wallet.

## Token features
- **Burnable**: Allow token holders to burn their tokens.
- **Ownable Contract**: Allow token owner to mint new tokens.
- **ERC-20** I choose the ERC-20 standard because it's the most used standard for token creation on Ethereum.    
It's also compatible with most of the wallets, exchanges and smart contracts.

## Deployment
- **Typescript and Ethers.js**: I choose this library to deploy my smart contract
  because it facilitates the interaction with Ethereum's blockchain.
- **[Remix](https://remix.ethereum.org/)**: And the IDE Remix compile my smart contract, and deploy it with this ether.js library.

## Security
- **Ownable Contract and Burnable**: I choose to restrict some functionalities like minting or burn tokens only by the contract owner.
- **[Multi signature with Safe Smart Contract](https://app.safe.global)** : To make any changes to the contract, i need to have the approval of the multi-sig address which is created by Safe Smart Contract.  
It offers a secure way to manage the contract because it requires the approval of multiple accounts

## Address of the token
- **[Etherscan](https://sepolia.etherscan.io/token/0xb5143adfb361c99cee17e474406fad189e28b56b?a=0x2cafb098f01d9199c04481cc3875c3acf4bf8da0)**: You can use this website to see the address of my token after deployment and all the contracts. As well, this is [my profile](https://sepolia.etherscan.io/address/0x2cafb098f01d9199c04481cc3875c3acf4bf8da0) on etherscan
