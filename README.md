# NFT Marketplace Smart Contract Development
## Final Project for course ELEN 6883 Blockchain
### Overview
This is the Final Project for ELEN 6883 Blockchain. The NFT marketplace smart contract will allow users to create, buy, sell, and trade unique digital assets represented as NFTs. The project will involve creating an ERC-721 compliant smart contract, designing a user interface for the marketplace, and implementing additional features to ensure the marketplace's security and usability.

### Installing
First, you will need to install the dependencies with: npm install.

Run the following command in your terminal after cloning the main repo:

```shell 
$ npm install 
```

Then, you will need to install Truffle globally by running the following command int your terminal:

```shell
$ npm install -g truffle
```

### Running the Tests
First, you will have to compile the smart contracts by running the following command in your terminal:

```shell
$ truffle compile
```

Then you will have to install and run Ganache to run your blockchain locally:

https://www.trufflesuite.com/ganache

we provide two tests, one for local and one for online. If you only want to test those locally, you need to remove NFTOnline.test.js from test file first and then do the following test. Similarly, if you want to do online test, you need to remove NFT.test.js from test file and then run following code.

The tests can be executed by running the following command:

```shell
$ truffle test
```

### Deployment on Local Blockchain
Deploy the contracts on your Ganache local blockchain by running the following command:

```shell
$ truffle migrate
```


### Deployment on Online platform

waiting to be filled


### User Interface Interact

You can interact with our user interface by using node. You need to change your direction into frontend first, and then run:

```shell
node app.js
```

Then, go to 

http://localhost:3000

and the interface of NFT marketplace will appear in front of you.

### Contributions of Each Team Member
Jing Wu(jw4288) and Xin Fang(xf2246) are responsible for:
1. designing, implementing and testing the NFT marketplace smart contract locally. 
2. UI designing and implementing. 
3. Implementing additional features, such as access control and error handling, to ensure the contract is reliable.

Yueyang Ying(yy3267) is responsible for deploying and testing the smart contract online, to make sure that it works well not only locally but also remotely.
