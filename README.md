# nft-lending-service

## Installation

Run

```bash
yarn
```

# Use of Hardhat

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```

## Deploying

### Deploying to the Rinkeby network.

```
export INFURA_KEY="<infura_key>"
export MNEMONIC="<metmask_mnemonic>"
yarn truffle migrate --network rinkeby
```

### Deploying to the mainnet Ethereum network.

```
yarn truffle migrate --network live
```
