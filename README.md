# NFT Marketplace

## Technology Stack & Tools

- Solidity (Writing Smart Contract)
- Javascript (React & Testing)
- [Ethers](https://docs.ethers.io/v5/) (Blockchain Interaction)
- [Hardhat](https://hardhat.org/) (Development Framework)
- [Ipfs](https://ipfs.io/) (Metadata storage)
- [React routers](https://v5.reactrouter.com/) (Navigational components)

## Requirements For Initial Setup
- Install [NodeJS](https://nodejs.org/en/), should work with any node version below 16.5.0
- Install [Hardhat](https://hardhat.org/)

## Setting Up
### 1. Clone/Download the Repository

### 2. Install Dependencies:
```
$ cd nft_marketplace
$ npm install
```
### 3. Boot up local development blockchain
```
$ cd nft_marketplace
$ npx hardhat node
```

### 4. Connect development blockchain accounts to Metamask
- Copy private key of the addresses and import to Metamask
- Connect your metamask to hardhat blockchain, network 127.0.0.1:8545.
- If you have not added hardhat to the list of networks on your metamask, open up a browser, click the fox icon, then click the top center dropdown button that lists all the available networks then click add networks. A form should pop up. For the "Network Name" field enter "Hardhat". For the "New RPC URL" field enter "http://127.0.0.1:8545". For the chain ID enter "31337". Then click save.  


### 5. Migrate Smart Contracts
`npx hardhat run src/backend/scripts/deploy.js --network localhost`

### 6. Run Tests
`$ npx hardhat test`

### 7. Launch Frontend
`$ npm run start`

### 8. Implementation

![Screenshot 2024-05-10 131339](https://github.com/progspac-vnn/NFT-Market/assets/83080783/a7ee417a-fc43-41ce-8912-57e3601e509b)
![Screenshot 2024-05-10 132145](https://github.com/progspac-vnn/NFT-Market/assets/83080783/35521f9c-c957-410d-86b5-6fd329082241)
![Screenshot 2024-05-10 131751](https://github.com/progspac-vnn/NFT-Market/assets/83080783/a7f9956e-019a-4753-b6f0-dabcbeccd8ad)

![Screenshot 2024-05-10 131740](https://github.com/progspac-vnn/NFT-Market/assets/83080783/43399963-ddf7-431f-bdfc-77f1dd31ad63)

![Screenshot 2024-05-10 131339](https://github.com/progspac-vnn/NFT-Market/assets/83080783/c533f952-dcfc-48bf-b806-f01c18f53a4f)

License
----
MIT

