## Creating Generative Art

### What is Generative Art?

Generative art is simply taking different types of colors, textures, images, and ideas then using an algorithm to combine them into thousands of unique pieces of art work or an NFT collection. 

You could write your own algo to do generative art or you could use an existing library like the Hashlips Art Engine, which we will be using in this lesson, along with Pinata to store our NFT images in a decentraized manner. 

![Generative Art Explainer](https://cadena.dev/wp-content/uploads/2022/06/cadena-generative-art-example.png)

⏰ Set aside at least 20 minutes for this lesson and remeber to take breaks as there are many steps involved that can be confusing at times but we will do our best to simplify things. 

Let's first outline at a high level the steps involved in this lesson.

1. Step 1: Download and install our fork of the Hashlips Library 
2. Step 2: Generate your own unique art work 
3. Step 3: Upload Images to Pinata
4. Step 4: Take CID from Pinata and add it to the metadata in HashLips 
5. Step 5: Upload Updated MetaData to Hashlips

## Download and install our fork of the Hashlips Library 

We've simplified the setup of the hashlips library so you can get setup faster, after this tutorial feel free to play around with the main library. 

Fork our repo of the Hashlips Art Library. You can download our fork for the library [here](https://github.com/CadenaDev/hashlips_art_engine) or clone it via the following command:

```bash
gh repo clone CadenaDev/hashlips_art_engine
```

 Once downloaded, open up the project folder in your favorite editor and  run `npm install` to set it up.

```bash
npm install
```

Now that you're all setup we're going to take a look at some commands, folders, and files to show you how Hashlip works.

Follow this video for all 5 steps.

### Files and Folder Structure 📂

| Folders/Files  |                                                              |
| -------------- | ------------------------------------------------------------ |
| /src/config.js | This is one of the main files where we will spend most of our time to configure the metadata of our collection, the layering, and how many pieces of art we want to generate. There are tons of other configurations you can read about [here](https://github.com/HashLips/hashlips_art_engine#usage-%E2%84%B9%EF%B8%8F). |
| build/images   | This is the out put of the images generated which will be uploading to pinata. |
| build/json     | This is where the meta data for each image will be stored as well |
| Layers         | This is where all your layers go, in our case our layers include backgrounds, logos, and planets. |

### Commands 🛠

| Commands            | What they Do                                                 |
| ------------------- | ------------------------------------------------------------ |
| npm install         | Install all the packages needed for the hashlips library     |
| npm run update_info | update the baseUri                                           |
| npm run build       | To generate art based on the paramters in your config file and the images in your layers folder. |



### IPFS
InterPlanetary File System (IPFS) - Think of IPFS as a peer to peer decentralize storage solution. Anyone can start their node to become a storage provider or upload files to the network. Every file uploaded to IPFS gets a unique content identifier (CID) assigned to it. The CID is pretty much a hash of random numbers and letters. If anything is changed in the file, the content identifier will change as well, making it perfect for storing files in an immutable way. 

We're going to be using Pinata to upload our files to the IPFS system and using our content identifiers in our project. Pinata is considered a noder operator and allows you to "pin" your files to the network via their APIs, hence the "pin" in Pinata. It is important to know IPFS is not a blockchain and is more similar to peer to peer torrent networks so there is no gurantee your files will be stored forever. Pinning allows you to store upto 1GB of your data for free. Due to the potential impermanent nature of storing on IPFS, storage solutions like Arweave have popped up to gaurantee permanent storage via their peer to peer storage network.



