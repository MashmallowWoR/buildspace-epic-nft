# Basic Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts.

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
// install needed packages 
npm install --save-dev @nomiclabs/hardhat-waffle ethereum-waffle chai @nomiclabs/hardhat-ethers ethers
npm install @openzeppelin/contracts
// test local network setup with sample script
npx hardhat run scripts/sample-script.js
// use .env for hardhat config variables
npm install dotenv
// test contract on local hardhat network
npx hardhat run scripts/run.js 
// deploy contract on Rinkeby test network
npx hardhat run scripts/deploy.js --network rinkeby
// install packages to connect to Ethscan
npm i -D @nomiclabs/hardhat-etherscan 
// verify contract on Ethscan
npx hardhat verify {CONTRACT_ADDRESS} --network rinkeby
```
