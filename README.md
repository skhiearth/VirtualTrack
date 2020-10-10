# VirtualTracker

Code snippets and supporting documentations for the **VirtualTracker** project built on Matic, Ethereum and Portis by *The Misfits* for HackTheMountains.

![Overview](https://github.com/skhiearth/VirtualTracker/blob/main/Screenshots/1.png)

## Instructions to run the project locally 
1. Go into the root folder of the project, named `SupplyChain` and run `npm install`.
2. Inside the root folder, run `truffle compile` to compile the Solidity smart contract to their JSON ABIs.
3. Run `truffle migrate --reset --network matic` to migrate the smart contracts to the Matic Mumbai test network or `truffle migrate --reset --network ropsten` to migrate to the Ropsten Test Network.
4. After migration, run `npm start` to start the Web Application.

Note: If you want to use your own account to deploy the contracts, open the `.secret` file and enter your mnemonic. To get the mnemonic of your account, you can go to Account Settings on Metamask or Export Account on Portis.

Note: If you decide to deploy using your personal account, ensure that there are enough MATIC/ETH tokens in your account. You can request tokens using the publically available [faucet for the Matic Mumbai network](https://faucet.matic.network/) or [faucets for the Ropsten network](https://faucet.ropsten.be/).


## Tech Stack:
* Smart Contracts: [Solidity](https://solidity.readthedocs.io/en/v0.7.3/)
* Wallet Integration: [Portis](https://www.portis.io/)
* Blockchain Network: [Matic](https://matic.network/) and [Ethereum Ropsten Test Network](https://ethereum.org/en/developers/docs/networks/)
* Front-end: [React](https://reactjs.org/)
* Package Manager: [npm](https://www.npmjs.com/)

![Portis](https://github.com/skhiearth/VirtualTracker/blob/main/Screenshots/4.png)
![React and Portis](https://github.com/skhiearth/VirtualTracker/blob/main/Screenshots/5.png)