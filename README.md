# Smart_Contract_KaseiCoin_Crowdsale
Develop, Deploy and Test a Crowdsale Smart Contract on a Local Blockchain
# Unit 21: Martian Token Crowdsale

![alt=""](Images/application-image.png)

## Background - Martian Token Crowdsale

The concept of this Smart Contract project is the development of a new monetary system for a hypothetical Mars colony. The monetary system will be base on blockchain technology, with an associated cryptocurrency named **KaseiCoin**. (Kasei means Mars in Japanese.)

KaseiCoin will be a fungible token that’s ERC-20 compliant. We intend to launch a crowdsale that will allow people who are "moving" to Mars to convert their earthling fiat money to KaseiCoin.

## Solidity Code Files

The following files are associated with the KaseiCoin project:

[KaseiCoin.sol](./Solidity_Code/KaseiCoin.sol)

[KaseiCoinCrowdsale.sol](./Solidity_Code/KaseiCoinCrowdsale.com)

## OpenZeppelin

The following OpenZeppelin Contracts/Libraries imported or inherited for the KaseiCoin project:

    * `ERC20`

    * `ERC20Detailed`

    * `ERC20Mintable`
    
    * `Crowdsale`

    * `MintedCrowdsale`

## Project Objectives

The following subsections will be performed to complete the project:

1. Develop a KaseiCoin Token Contract - smart contract that defines KaseiCoin as an ERC-20 token.

2. Develop a KaseiCoin Crowdsale Contract - the crowdsale contract will manage the entire crowdsale process. This process will allow users to send ether to the contract and receive KaseiCoin tokens, or **KAI**, in return. The contract will automatically mint the tokens and distribute them to a buyer in one transaction.

3. Develop a KaseiCoin Deployer Contract - The Crowdsale will be deployed to a local blockchain by using Remix, MetaMask, and Ganache.

4. Deploy and Test the Crowdsale on a Local Blockchain - Deployment and testing results contained in **Evaluation Evidence** section.

## Evaluation Evidence
1. Deploy the crowdsale to a local blockchain by using Remix, MetaMask, and Ganache.

* Successful Deploy of KaseiCoin.sol

![KaseiCoin Deployment](Images/KaseiCoin_Deploy.png)

* Successful Deploy of KaseiCoinCrowdsale.sol Minter Contract

![KaseiCoinCrowdsale Deployment](Images/KaseiCoinCrowdsale_Minter.png)

* Successful Deploy of KaseiCoinCrowdsale.sol Deployer Contract

![KaseiCoinCrowdsale Deployment](Images/KaseiCoinCrowdsale_Deployer.png)

2. Test the functionality of the crowdsale by using test accounts to buy new tokens and then checking the balances of those accounts.

* Successful Deploy of KaseiCoinCrowdsale.sol

![KaseiCoinCrowdsale Deployment](Images/KaseiCoinCrowdsale_Deployer.png)

3. Review the total supply of minted tokens and the amount of wei that the crowdsale contract has raised.


In the `README.md` file of your GitHub repository for this homework assignment, you’ll create a section named Evaluation Evidence. In this section, you’ll share screenshots of your work from each subsection of the assignment.

Take a screenshot of the successful compilation of the contract, and add it to the Evaluation Evidence section of the `README.md` file for your GitHub repository.


7. Take a screenshot of the successful compilation of the contract, and add it to the Evaluation Evidence section of the `README.md` file for your Git repository.







8. Create a GitHub repository and a `README.md` file that explains the process for buying KaseiCoin.

Make sure that your `README.md` file includes screenshots that illustrate the functionality of your contracts as the earlier instructions detailed.

You can also record your interactions with the executed contract as a short video or an animated GIF. To record a video, you can use the following tools:

* If you’re working on macOS, you can create a screen recording by using the built-in QuickTime player. To learn more about this tool, refer to [Use QuickTime Player](https://support.apple.com/en-us/HT208721#quicktime) in the Apple Support documentation.


* To create an animated GIF, you can use [Recordit](https://recordit.co/) on either macOS or Windows.

---
