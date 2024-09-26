# Blockchain_Application
# Engineering Blockchain Applications Portfolio


---

## Table of Contents
- [Project 1: ERC-721 Token Standard Smart Contract](#project-1-erc-721-token-standard-smart-contract)
  - [Overview](#overview)
  - [Setup](#setup)
  - [Implementation](#implementation)
  - [Results](#results)
- [Project 2: Hyperledger Fabric Supply Chain Contract](#project-2-hyperledger-fabric-supply-chain-contract)
  - [Overview](#overview-1)
  - [Setup](#setup-1)
  - [Implementation](#implementation-1)
  - [Results](#results-1)
- [Skills Acquired](#skills-acquired)
- [References](#references)

---

## Project 1: ERC-721 Token Standard Smart Contract

### Overview
In Project 1, an ERC-721 token standard smart contract was created on the Ethereum ecosystem using the Solidity programming language and deployed on the Polygon Mumbai Testnet.

### Setup
1. **MetaMask**: Used MetaMask to connect to the Polygon Mumbai Network for gas fee payments.
2. **Polygon Mumbai Testnet**: Deployed the smart contract on the Polygon Mumbai Testnet for testing purposes.
3. **Polygon Mumbai Testnet Faucet**: Acquired test tokens (MATIC) for gas fees.
4. **Remix IDE and Solidity**: Set up the development environment in Remix IDE for smart contract development.

### Implementation
- Created a constructor to receive parameters (name, symbol, and message).
- Overrode return functions to output the received parameters.
- Compiled and deployed the smart contract to the Polygon Mumbai Testnet.

### Results
- Successfully deployed the smart contract, enabling interaction with the Ethereum blockchain.
- The contract returned the expected output payload confirming its functionality.

---

## Project 2: Hyperledger Fabric Supply Chain Contract

### Overview
In Project 2, a supply chain contract was implemented on the Hyperledger Fabric platform using the Go programming language.

### Setup
1. **Project Skeleton**: Cloned the project skeleton source code to the local machine.
2. **Docker and Tools**: Installed Docker, jq, and cURL.
3. **Test Network**: Set up a local blockchain environment for testing.

### Implementation
- Created functions: 
  - `CreateProduct`
  - `UpdateProduct`
  - `TransferOwnership`
  - `QueryProduct`
- Initialized two original products in the ledger.
- Deployed the smart contract on the network and committed the chaincode.

### Results
- Successfully invoked the chaincode functions, validating the supply chain contract's functionality.

---

## Skills Acquired
Throughout the course and project execution, the following skills were acquired:
- Proficiency in using digital wallets (MetaMask).
- Understanding of cryptography in blockchain technology.
- Deep knowledge of the Ethereum ecosystem and Polygon technology.
- Mastery of Solidity and Remix IDE for smart contract development.
- Hands-on experience with Hyperledger Fabric and Go programming language.

---

## References
1. [Ethereum Whitepaper](https://ethereum.org/en/whitepaper/)
2. [Polygon Whitepaper](https://polygon.technology/papers/pol-whitepaper)
3. [ERC721 Standard Smart Contract](https://docs.openzeppelin.com/contracts/3.x/erc721)
4. [Hyperledger Fabric Documentation](https://hyperledger-fabric.readthedocs.io/en/release-2.2/smartcontract/smartcontract.html)

