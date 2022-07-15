# Web3 blog

### Running project locally

1. start the local network
```shell
npx hardhat node
```

2. deploy smart contracts
```shell
npx hardhat run scripts/deploy.js --network localhost
```

or

```shell
npm run deploy:local
```

3. Importing the test account into MetaMask (only one time)

`Use private key from first account. Show test network in MetaMask. Switch to "Localhost 8545". Next, "Import account" with private key.`

4. Run application

```shell
npm run dev
```

### From Nader's tutorial

`https://dev.to/edge-and-node/the-complete-guide-to-full-stack-web3-development-4g74`
