# smart-order/core-contract

introduction

## How to use
### Part 1 : Setting up
1. `cd core-contract`
2. `npm install`

### Part 2 : Smart-contracts
Open a new console and type `truffle develop` to open a truffle invite & setup a local development blockchain network.

Then in the truffle console you'll be able to execute the following commands :
1. `compile` to compile your contracts
2. `migrate` to deploy your contracts to the network. 
You can use `--reset` in case of contract update to force recompilation.

## Running unit tests
Run `truffle test` to run tests associated with your solidity smart contracts. The test folder for this can be found in the `test` directory at the root level of this project


## Technologies & Languages
1. Truffle (Solidity)
