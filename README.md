
## Installation

Make sure you have the following ready:
- `npm` installed
- [Truffle](https://www.trufflesuite.com/docs) installed globally via `npm install -g truffle` (developped on v5.3.2).
- Cloned the repo via `git clone`

## Deployment

In your terminal, go to the DEX repo and type:
`cd blockchain`
`npm install`

To deploy your smart-contracts:

PLEASE UNDERSTAND THAT THIS IS A PROTOTYPE. WHILE IT IS WORKING FINE, THIS DEX IS NOT READY TO GO LIVE YET.
- Run `truffle develop`, then `test` to make sure everything is running smoothly.
- Run `truffle migrate --network <<network name here>>` to deploy to the network of your choice. So for Kovan, type `truffle migrate --network kovan`
