# VirtualTracker

Code snippets and supporting documentations for the VirtualTracker project built on Matic and Portis by The Misfits for HackTheMountains.

## Instructions to run the project locally 
1. Go into the root folder of the project, named `SupplyChain` and run `npm install`.
2. Inside the root folder, run `truffle compile`.
3. Run `truffle migrate --reset --network ropsten` to migrate the smart contracts to the Ropsten test network.
4. After migration, run `npm start` to start the Web Application.

Note: If you want to use your own Ethereum account to deploy the contracts, open the `.secret` file and enter your mnemonic. To get the mnemonic of your account, you can go to Account Settings on Metamask or Export Account on Portis.
Note: If you decide to deploy using your personal account, ensure that there are enough ETH tokens in your account. You can request tokens using any of the publically available faucets for the Ropsten network.
