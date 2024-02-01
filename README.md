# Martian Token Crowdsale
![application-image](https://github.com/ahcano/martian_crowdsale/assets/141194281/8081ea12-e8fe-4d96-bab1-3d46cae560ed)

## Background
A crowdsale is the process of raising capital by creating an initial coin offering, or ICO.
An initial coin offering, or ICO, is a fund-raising mechanism where new coins or tokens are offered in exchange for more-popular cryptocurrencies, like bitcoin or ether

## Hypothetical Business Case 
After waiting for years and passing several tests, you were selected by the Martian Aerospace Agency (a fictitious organization) to become part of the first human colony on Mars. As a prominent fintech professional, you were chosen to lead a project developing a monetary system for the new colony. You decide to base this new system on blockchain technology and to define a new cryptocurrency, named KaseiCoin. (Kasei means Mars in Japanese.)

KaseiCoin will be a fungible token that’s ERC-20 compliant. You’ll launch a crowdsale that will allow people who are moving to Mars to convert their earthling money to KaseiCoin.

## Project Objectives:
* Create a fungible token that’s ERC-20 compliant and that will get minted via a crowdsale contract created based on the Crowdsale contract from the Solidity library.
* Create a crowdsale contract which manages the entire crowdsale process. Allowing users to send ether to the contract and receive KAI, or KaseiCoin tokens, in return. The contract automatically mints the tokens and distributes them to buyer(s) in one transaction.

## Compiled Contract
![compiled_KaseiCoinToken_contract_pragmav517](https://github.com/ahcano/martian_crowdsale/assets/141194281/7b8548f7-6797-4c86-bcb6-3de29319fe23)

## Constructor Parameters: Name, Symbol, Initial_Supply
A constructor is a specialized function that we can use to pass initial values to our contract. In the case of Kasei Coin, we can use the constructor to pass values for the initial_supply of tokens, the name, the symbol, and the number of decimals that are associated with the token distribution.

![constructor_parameters](https://github.com/ahcano/martian_crowdsale/assets/141194281/03fefab3-c73a-4aa4-b3d6-1442c2e678c4)

## Code to create contracts: KaseiCoin and KaseiCoinCrowdsale
![step2and3_compiled_KaseinCoinCrowdsale_contract_pragmav517](https://github.com/ahcano/martian_crowdsale/assets/141194281/bbb8c8dd-bd93-4ad1-a8c8-b8e490d865b9)

## Ganache is a desktop application that was used to locally implement a test version of the Ethereum blockchain. The first Ganache account was selected to be imported into Metamask.
![selecting_account_to_import](https://github.com/ahcano/martian_crowdsale/assets/141194281/237c3d2b-9f4a-4056-b9ab-0f79118218ad)

## To import the account, the private key was entered in Metamask
![importing_account_to_Metamask](https://github.com/ahcano/martian_crowdsale/assets/141194281/6c396bc7-3e90-48e6-ab30-0eb61a54aeee)

## The previous step allowed for the Ganache account to be linked in REMIX
![linked_Ganache_account_in_REMIX](https://github.com/ahcano/martian_crowdsale/assets/141194281/a3096896-deb0-4f60-bd8d-da051f576d12)

## In parallel, below is the verification that the account is connected to REMIX
![Metamask_imported_Ganache_account](https://github.com/ahcano/martian_crowdsale/assets/141194281/aa91c05f-14ef-442e-b743-31476b097151)

## Token Buy transaction - approval through Metamask
![Metamask_approval](https://github.com/ahcano/martian_crowdsale/assets/141194281/694dbf75-3478-46db-85b4-742118214bbe)

## Final Results
![Final_Results](https://github.com/ahcano/martian_crowdsale/assets/141194281/11e7e72f-a3ee-4518-8b16-6d64942c5c51)

The image above shows the successful transactions
* Two Deployed Contracts: KaseiCoin and KaseiCoinCrowdsale
* The contract addresses: 0x55081b0d7293Db956f07AdC968288bA838376feE   0x60fFd5Bef7E72df49fce36fb624D3603fEbC5cF5
* The Wei raised through crowdsale of 10000000000000000000 Wei (10 ETH)

## Ganache also recorded the Contract transaction
 ![Ganache_ContractCall](https://github.com/ahcano/martian_crowdsale/assets/141194281/cc30b6ca-15c6-4f56-bb6b-fc23ee83f4f6)

### Contributor
Ana Cano - Author

### License
Copyright (c) 2011-2017 GitHub Inc. Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions: The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software. THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
