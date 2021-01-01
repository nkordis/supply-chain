## Supply Chain Coffee Project
Ethereum DApp that demonstrates a Supply Chain flow for a coffee item.  

## Libraries

* Truffle v5.1.58 (core: 5.1.58)
* Solidity ^0.4.24 (solc-js)
* Node v12.13.1
* Web3.js v1.2.9

## How To Start
1. Clone this repository

2. Change directory to ```project-6``` folder and install npm packages:
```
npm install

```
3. Launch ganache:
```
ganache-cli -m "<PUT HERE YOUR WALLET MNEMONIC>"
```
4. In a separate terminal window, Compile smart contracts:
```
truffle compile
```
5. Migrate smart contracts to the locally running blockchain, ganache-cli:
```
truffle migrate
```
6. Test smart contracts:
```
truffle test
```
7. In a separate terminal window, launch the DApp:
```
npm run dev
```

### Deployment  
Deploy to Rinkeby network:  
`compile`  
`truffle migrate --reset --network rinkeby`

## Deployed contract (Rinkeby)
* Transaction hash – 0x47bc91c814c9cae0f69878f6adff54792a8a3a1c7c77cae93ad8665a576e84ad
* Contract address – 0xFD4E035FF4BAdf58FD3A3bF1C5ACdF52747d9Cd5

* https://rinkeby.etherscan.io/address/0xFD4E035FF4BAdf58FD3A3bF1C5ACdF52747d9Cd5

