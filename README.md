# Willow | web3 Real Estate NFT Marketplace
###
![willowImgv2](https://user-images.githubusercontent.com/83500098/235682263-6386b3fc-bd22-4b6d-8606-081e7809fa31.png)
###
This web3 real estate NFT marketplace allows users to publish NFT metadata on IPFS and list homes for sale represented as ERC721 tokens. The smart contract enables owners to mint tokens and accept payment in Ether. Once a user purchases property, they can trade their NFT and send tokenized real estate to any Ethereum address.
## Technology Stack

- Solidity
- Javascript
- Ethers.js
- React.js
- Node.js
- Hardhat

### Dependancies
- MetaMask (reset account on the Hardhat Network)

## Run this dapp
### 1. Clone or Download the Repository

### 2. Install Dependencies:
`$ npm install`

### 3. Run tests
`$ npx hardhat test`

### 4. Start Hardhat node
`$ npx hardhat node`

### 5. Run deployment script
In a separate terminal run:
`$ npx hardhat run scripts/deploy.js --network localhost`

### 7. Start frontend
`$ npm run start`
