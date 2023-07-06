# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```
This dApp Will do the following things: 
Anyone who owns a CryptoDevs NFT can create a proposal to purchase a different NFT from an NFT marketplace
Everyone with a CryptoDevs NFT can vote for or against the active proposals
Each NFT counts as one vote for each proposal
Voters cannot vote multiple times on the same proposal with the same NFT
If the majority of the voters vote in favor of the proposal by the deadline, the NFT purchase happens automatically from the marketplace
