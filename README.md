# faucet-sdk

![Tests](https://github.com/abigger87/faucet-sdk/workflows/Test/badge.svg)
![Publish GitHub Release and NPM Package](https://github.com/abigger87/faucet-sdk/workflows/Publish/badge.svg)

[![NPM](https://nodei.co/npm/faucet-sdk.png)](https://npmjs.org/package/faucet-sdk)

SDK for https://github.com/abigger87/faucet

#### Upgrading

Must change `FaucetFactory` address in two locations:

-   `src/index.ts`
-   `src/__tests__/FaucetFactory.test.ts`

To upgrade a contract, we must update the contract ABI in `src/abi`
