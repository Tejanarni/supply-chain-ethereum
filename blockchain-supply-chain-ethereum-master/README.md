# SupplyChain Mayank Gupta
## Setup
**IMPORTANT**: You need to have npm and truffle already installd
1. Checkout the GitHub Repo
```
$ git clone https://github.com/Mayank0307/blockchain-real-estate-ethereum.git
```
2. Install dependencies using npm
```
$ cd EthereumCoffeeSupplyChain
$ npm install
```
3. Run Truffle tests
```
$ truffle develop
truffle> test
```

4. Compile Smart Contracts using Truffle
## truffle compile
![Screenshot (829)](https://user-images.githubusercontent.com/52233220/84560426-ab901180-ad61-11ea-99fc-73ae72273d02.png)

## Deploy Smart Contracts to the Rinkeby Testnet

## truffle migrate --network rinkeby
![Screenshot (830)](https://user-images.githubusercontent.com/52233220/84560440-c4002c00-ad61-11ea-84bd-80586917e9bc.png)

## UML digrams:
## ACTIVITY DIGRAM:

![Coffee_Activity](https://user-images.githubusercontent.com/52233220/84560462-07f33100-ad62-11ea-9553-bf185f90e969.png)

## CLASS DIGRAM:
![Coffee_Class](https://user-images.githubusercontent.com/52233220/84560471-248f6900-ad62-11ea-8a57-ac3503083f7a.png)

## STATE DIGRAM:
![Coffee_State](https://user-images.githubusercontent.com/52233220/84560473-33761b80-ad62-11ea-8d11-0c4a762bb297.png)

## SEQUENCE DIGRAM:
![Coffee_Sequence](https://user-images.githubusercontent.com/52233220/84560481-45f05500-ad62-11ea-9d71-b729f5a7c674.png)


### Libraries used
The only Library used was `truffle-hdwallet-provider` to deploy the Smart Contracts to the Rinkeby Testnet using infura.

### Usage of IPFS
The IPFS (Interplanetary File System) wasn't used for this project, but it should be used for similar projects to provide a fully decentralized service. It wasn't used because I considered it out of Scope.



