
## Smart Contract

Before we dive into the code of our smart contract, let's first think about what goals we want it to accomplish.

1. Sell our NFT's at a certain price.
2. Have someone with a wallet purchase (mint) our NFT's at that price. Minting is simply transfering the ownership of an NFT from the contract to a wallet address for a price.
3. Withdraw the money we made from our NFT sales from our smart contract.

This is as simple as our smart contrat needs to be and infact you can use [OpenZepplin's Wizard](https://docs.openzeppelin.com/contracts/4.x/wizard) to create an ERC 721 contract that does just this. There are NFT Smart Contracts that range in complexity but for our lesson we're going to keep it simple so you can learn the fundementals. 

You can find the tutorial to setup hardhat [here](
https://app.cadena.dev/ZHjzLozd3mCsAcgMfeHE/lesson/ethereum-101/lesson-eth-6/6) and deploy a smart contract with hardhat [here](https://app.cadena.dev/ZHjzLozd3mCsAcgMfeHE/lesson/ethereum-101/lesson-eth-7/7). Alternatively you can also deploy your smart contract to Rinkeby using Remix. 

You view the full code for our ERC-721 contract [here](https://gist.github.com/saeedjabbar/ef711176780db78df65ac7ae15d9e3c8) and get the hardhat repo [here](https://github.com/CadenaDev/cadena_nft_smartcontract).



## Setting Up Our ERC-721 Smart Contract

<iframe width="560" height="315" src="https://www.youtube.com/embed/Vebxr0-6moQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<script src="https://gist.github.com/saeedjabbar/ef711176780db78df65ac7ae15d9e3c8.js"></script>
