# Crypto Star Decentralized APP ( aka DAPP)
This is the second project for @Udemy Blockchain developer Nanodegree. The purpose of this
project is to familiarize with Ethereum dapp development.

## What this dapp will do:
"Crypto Star" dapp is a decentralized application that users can create , own,
transfer, put for sale, buy and exchange Stars. The smart contract implements the 
ERC721 token standard, a standard interface for non-fungible tokens, also known as deeds. 
This contract is uploaded to Rinkeby Ethereum test network.

Contract address: 0x051D129B38A2Dd6471894721d2117C59b3bA95b5
ERC-721 Token Name: Crypto Star Token
ERC-721 Token Symbol: CST

## Technology used for this project:
    - Solidity version >=0.4.24
    - Truffle version v5.1.20
    - Openzeppelin 2.1.2
    - npm
    - js
And for testing:

    - Chai
    - Mocha
        
### Run Crypto Star dapp:
    npm install
    truffle compile
    truffle migrate
    cd app
    npm run dev
