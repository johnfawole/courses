# Setting Up Our NFT Minter DAPP



The react dapp for the boiler plate of our lesson can be found [here](https://github.com/CadenaDev/cadena_nft_minter_template).

Note: IPFS can be slow at times so if you don't see your images load, it can take sometime. You can also experiment with using the Cloudflare IPFS gate way, found [here](https://developers.cloudflare.com/web3/ipfs-gateway/).  



### Video Walkthrough 

<iframe width="100%" height="515" src="https://www.youtube.com/embed/JXBFrSmYPcQ" title="Creating an NFT Minter DAPP with React" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

1. Get your contract address and update it in the contract address variable in the boiler plate.

```javascript
const contractAddress = 'INSERT_YOUR_CONTRACT_ADDRESS_HERE';
```



2. Copy your compiled smartcontract ABI file from hardhat over to the contracts folder in the react app and update the **abi** variable to reflect accordingly. 

```javascript
import abi from "./contracts/CadenaNFTS.json";
```

3. Copy over the CID (content id) of your metadata folder on Pinata and update the **metadataURI** variable.

```javascript
const metadataURI = `https://gateway.pinata.cloud/ipfs/INSERT_YOUR_JSON_CID_HERE/${tokenId}.json`
```

4. Copy over the contents of your **_metadata.json** from  hashlibs, located in the **build/json** folder into **nft_metadata.json**

### Viewing your Minted NFTs 

You can see if your NFT's have been minted by viewing them on the Rarible or OpenSea testnets. To do so simply take your smart contract address and paste it in the search bar.

| Testnets | Links                        |
| -------- | ---------------------------- |
| Rarible  | https://rinkeby.rarible.com/ |
| OpenSea  | https://testnets.opensea.io/ |



### Earning your NFT Certificate 

To earn your NFT Certificate, create a minter dapp with your own unique art work and share in the #showcase channel or tag us on twitter at @cadenadev for a shoutout. Your dapp must include the following components:

1. An ERC-721 smart contract.
2. Your own unique art. Get creative here, you can use your favorite colors, shapes, textures, photos, and combinations you like.
3. A dapp to mint your art work. Please make your DAPP live by uploading it. They are many free hosts like vercel, netlify, etc.

**Submitting Your Project**

Email us at team@cadena.dev with your live project url, github repo and once approved we will issue you an NFT Certificate. 

