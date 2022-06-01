# Getting Started

We want you to avoid tutorial hell and jump into building projects from day one. If you don’t know something as you move along, do a quick google search or ask in our discord channel.

Avoid getting stuck and going down rabbit holes. One of your goals should be to get a high level understanding of how all the moving pieces of developing on the blockchain come together. On your second go, you can go more in depth or come up with your own projects.

Our main goal is to get to done. If you’re stuck, you have our permission to copy and paste the sample code just so that you can move on to the next lesson and get to done. 

## A Note on Security 🚨
***

There are numerous sophisticated attempts to hack, phish and steal crypto currencies since there is no central authority to over see the blockchain and you cannot undo any transaction. 

**Double-check** all urls, even the urls you click through searching on Google to make sure they are accurate. Never share your seed and private keys with anyone and make sure to back them up in multiple secure places. 

A good rule of thumb is not to trust anyone in the MetaVerse, impersonation is a common mechanism for theft. Always triple check links and wallets you send digital assets to and do not store any credentials in your main code base that is pushed to GitHub. We will be using [dotenv](https://www.npmjs.com/package/dotenv) to store our credentials locally only. 

## Prerequisites
***

***
## Wallets

To get started you will need a wallet. Your wallet will act as your login to access the Ethereum network. Your public key is like your username and your private key is like your password. 

**Steps to Setup Your Wallet**
1. Download and Install MetaMask from the official website.
2. Switch your network over to the Rinkeby testnet
3. Deposit some fake ether.
4. Share your wallet address in our discord #general channel

## Step 1: Installing your MetaMask Wallet

We will be using [MetaMask](https://metamask.io/) for our tutorials so download and install metamask from their official website which is [www.metamask.io](www.metamask.io). Double check the URLs as there are many fake websites for MetaMask. Please store your seed and private keys in a secure place. 

## Step 2: Using the Rinkeby Testnetwork

Once you have your wallet installed. We will be switching off of the main ethereum network to a test network. A test-network mimics the functionality of the real network so that we can deploy and test our smart contracts with out wasting real money on gas. For our tutorials we will be using the Rinkeby test Network. 

To switch to the Rinkeby test network, do the following:
1. Go to the following url and click Connect Wallet: https://chainlist.org/chain/4

If this doesn't work you can do the following:
1. Go to [Chainlist.org](https://chainlist.org), click testnets located in the top middle of the website. 
2. Type in Rinkeby
3. Click Connect Wallet.

## The Manual Way to Connect
Click on the fox icon in your browser, then click Ethereum Mainnet located at the top center, then in the drop down menu click Rinkeby Test Network. 
(If you dont find Rinkeby Test Network in the dropdown menu, go to settings => advanced => then switch on the 'show test networks' button. Hopefully the Rinkeby Test Network will showup along with other test networks).

## Step 3: Deposit Some Fake Ether

Next you will need send your self some fake Ether via what’s known as a faucet. Here are a list of faucets, again double-check these as sometimes the faucets are out of fake ether. We recommend using RBF.

- RBF: https://www.rinkebyfaucet.com/
- MyCrypto: https://app.mycrypto.com/faucet
- Rinkeby: https://faucet.rinkeby.io
- MetaMask: https://faucet.metamask.io
- Chainlink: https://faucets.chain.link/rinkeby
- You can ask us in the discord if you run out of fake Ether.

## Step 4: Share Your Success
Congrats🎉 Share with us your public wallet address [#general](https://discord.gg/UQayXxzazc) channel in our discord so we can celebrate along with you or feel free to tweet about it and tag us at [@cadenadev.](https://twitter.com/cadenadev) 

***
## Solidity

Smart contracts are programmed in Solidity. Solidity is fairly easy to pick up, if you don’t know it, you will pick it up as we move along. It's concepts from C++, Python and JavaScript so it should be familiar enough. 

Here’s a cheat sheet to speed up your learning:

- A high level overview of the Solidity language: [https://solidity-by-example.org/](https://solidity-by-example.org/)
- CryptoZombies is another amazing resource to pick up Solidity as well: https://cryptozombies.io

***
## JavaScript** 

You’ll need to have an intermediate understanding of JavaScript or another programming language to get through this tutorial. If you are new to coding, we recommend learning a coding language like JavaScript or Python first. We will be using some Javascript libraries like Ethers.js to interact with our smart contract. 

***
## Code Editor

You can use your favorite code editor but download the package that allows for Solidity syntax highlighting. For some lessons we will use Remix, an online development environment for smart contracts ([remix.ethereum.org/](http://remix.ethereum.org/)).

➡️ **Action Item** Share with us your public address in the #general [discord](https://discord.gg/UQayXxzazc) and let us know what you're hoping to build after you finish your course.
