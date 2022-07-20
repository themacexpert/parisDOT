# Remote Execution with XCM @parisDOT 2022
![Banner Image](https://pbs.twimg.com/profile_banners/1532112897786138632/1657021506/1500x500)

This guide contains all the links you'll need for the Remote Execution with XCM Workshop - so you only have to scan 1 QR code at the beginning. We won't assume any pre-existing account setup, so we will start from a blank slate. 

### Initial Setup

1. [Install MetaMask](https://metamask.io/)
2. [Add Moonbase Alpha Network to MetaMask](https://docs.moonbeam.network/)
3. [Get funds from the faucet](https://apps.moonbeam.network/moonbase-alpha/faucet/)
4. [Swap some (not all) DEV tokens for xcUNITS](https://moonbeam-swap.netlify.app/#/swap)

### Calculating a Sovereign Address
- [Clone the xcmTools repo](https://github.com/albertov19/xcmTools)
- [Shawn Tabrizi's Utilities](https://www.shawntabrizi.com/substrate-js-utilities/)

### Account Setup
- [Create a New Account on the Moonbase Relay Chain](https://polkadot.js.org/apps/?rpc=wss%3A%2F%2Ffrag-moonbase-relay-rpc-ws.g.moonbase.moonbeam.network#/accounts)
- [Import the ALICE Account on the Moonbase Alpha Parachain](https://polkadot.js.org/apps/?rpc=wss%3A%2F%2Fwss.api.moonbase.moonbeam.network#/accounts) Private Key: 0x28194e8ddb4a2f2b110ee69eaba1ee1f35e88da2222b5a7d6e3afa14cf7a3347
- Also, import the ALICE account to your MetaMask

### Calculating the Derivative Account
- [Clone the PolkaTools repo](https://github.com/albertov19/PolkaTools)
- [Check account balance of derivative account](https://polkadot.js.org/apps/?rpc=wss%3A%2F%2Ffrag-moonbase-relay-rpc-ws.g.moonbase.moonbeam.network#/chainstate)

### Transfer 
- [Fill out the transfer information on the relay chain to get the call bytes but don't submit here](https://polkadot.js.org/apps/?rpc=wss%3A%2F%2Ffrag-moonbase-relay-rpc-ws.g.moonbase.moonbeam.network#/extrinsics)
- [Initiate the remote transfer transaction on the Moonbase Alpha Parachain](https://polkadot.js.org/apps/?rpc=wss%3A%2F%2Fwss.api.moonbase.moonbeam.network#/extrinsics)
