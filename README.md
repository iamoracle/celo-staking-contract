# Staking Contract

Staking and reward contracts are popular mechanisms for incentivizing participation in the activities of a blockchain network. Users can use these contracts to lock up their tokens as collateral to earn rewards. This article will look at using the Solidity programming language to create a staking and reward contract.




## Install Dependencies

```bash 
yarn install
```

# Setup

1. Change the token in [./scripts/deploy.js](./scripts/deploy.js) to your custom token.

2. Rename [./env_example](./env_example) to `.env` and paste in your private key.

## Deploy

```bash 
npx hardhat run ./scripts/deploy.js
```
