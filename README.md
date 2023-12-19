# Arbitrum Stylus + Scaffold-ETH 2

## Overview

Arbitrum Stylus + Scaffold-ETH 2

Deploy a rust smart contract with Arbitrum Stylus and interact with it with Scaffold Eth 2 front end, with a contract live on Stylus Testnet:
https://stylus-testnet-explorer.arbitrum.io/


## How to use
To deploy on Stylus Testnet, insert your private key in an .env file in the packages/stylus repo. then you can run the following commands

```bash
 cargo stylus check   
 cargo stylus deploy --private-key-path=./.env
```


## Test
You can interact with the rust smart contract on Arbitrum Stylus Testnet through hardhat

```bash
  cd packages/stylus/hardhat
  yarn install
  yarn hardhat run scripts/initialize.js   
```

## Acknowledgmenets
- Scaffold Eth 2
- Arbitrum Stylus