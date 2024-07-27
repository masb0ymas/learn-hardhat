# Learn Hardhat

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a Hardhat Ignition module that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat vars set INFURA_API_KEY

npx hardhat vars set SEPOLIA_PRIVATE_KEY

npx hardhat vars set ETHERSCAN_API_KEY
```

#### For Compile
```shell
yarn compile
```

#### For Deploy
```shell
yarn deploy:sepolia
```

#### For Verify Deploy Contract
```shell
yarn verify:sepolia -- <contract_address>
```