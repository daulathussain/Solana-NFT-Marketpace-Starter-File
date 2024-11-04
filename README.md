# Full-Stack Solana Blockchain NFT Marketplace DApp

Build and Deploy a Full-Stack Solana Blockchain NFT Marketplace DApp with Next.js, Context API, and Metaplex

Learn how to build and deploy a full-stack NFT marketplace on the Solana blockchain using Next.js, Context API, and Metaplex. This comprehensive guide covers setting up your development environment, integrating Metaplex for NFT creation, managing state with Context API, and deploying your marketplace. Perfect for developers looking to leverage Solana’s speed and low fees to launch a scalable NFT platform.

## Project Overview

![alt text](https://www.daulathussain.com/wp-content/uploads/2024/10/Full-Stack-Solana-Blockchain-NFT-Marketplace-DApp.jpeg)

Kindly follow the following Instructions to run the project in your system and install the necessary requirements

- [Final Source Code](https://www.theblockchaincoders.com/sourceCode/build-and-deploy-a-full-stack-solana-blockchain-nft-marketplace-dapp)

#### Setup Video

- [Final Code Setup video](https://youtu.be/9m0x0VRKIiI?si=mJwGbWLDh0lgRXPF)

```https://code.visualstudio.com/download
  WATCH: Setup & Demo Of Project
```

#### Install Vs Code Editor

```https://code.visualstudio.com/download
   GET: VsCode Editor
```

#### NodeJs & NPM Version

```https://nodejs.org/en/download
  NodeJs: v18.12.1 || LATEST
  NPM: 8.19.2 || LATEST
```

#### Clone Starter File

```
  GET: Project Starter File Download
```

All you need to follow the complete project and follow the instructions which are explained in the tutorial by Daulat

## Final Code Instruction

If you download the final source code then you can follow the following instructions to run the Dapp successfully

#### What You Will Get

Once you download the final source code, you will get a ZIP file, then you will have 2 FOLDERS & README file which contain all the instructions to run the project and set video

#### Setup Video

```
  WATCH: Setup & Demo Of Project
  URL: https://youtu.be/9m0x0VRKIiI?si=mJwGbWLDh0lgRXPF
```

#### Final Source Code

```
  Download the Final Source Code
URL: https://www.theblockchaincoders.com/sourceCode/build-and-deploy-a-full-stack-solana-blockchain-nft-marketplace-dapp
```

#### Install Vs Code Editor

```
  GET: VsCode Editor
  URL: https://code.visualstudio.com/download
```

#### NodeJs & NPM Version

```
  NodeJs: v18.12.1 || LATEST
  NPM: 8.19.2 || LATEST
  URL: https://nodejs.org/en/download
```

#### Test Faucets

Alchemy will provide you with some free test faucets which you can transfer to your wallet address for deploying the contract

```
  Get: Free Test Faucets
  URL : https://beta.solpg.io/
  URL : https://faucet.solana.com/
```

#### Solana Playground

We are using Solana Playground for deploying the contract and generation of the ABI in the project, but you can use any other tools like Hardhat, etc.

```
  OPEN: Solana Playground
  URL: https://beta.solpg.io/
```

#### Solana Network

```
  OPEN: Solana Network
  URL: https://explorer.solana.com/
```

## Important Links

- [Get Pro Blockchain Developer Course](https://www.theblockchaincoders.com/pro-nft-marketplace)
- [Support Creator](https://bit.ly/Support-Creator)
- [All Projects Source Code](https://www.theblockchaincoders.com/SourceCode)

## Authors

- [@theblockchaincoders.com](https://www.theblockchaincoders.com/)
- [@consultancy](https://www.theblockchaincoders.com/consultancy)
- [@youtube](https://www.youtube.com/@daulathussain)

#### PACKAGE JSON

```
{
  "name": "solana-nfts-marketplace",
  "version": "0.1.0",
  "private": true,
  "scripts": {
    "dev": "next dev",
    "build": "next build && next export",
    "start": "next start",
    "lint": "next lint"
  },
  "dependencies": {
    "@formspree/react": "^2.5.1",
    "@metaplex/js": "^4.12.0",
    "@shyft-to/js": "^0.2.40",
    "@solana/wallet-adapter-phantom": "^0.9.24",
    "@solana/wallet-adapter-react": "^0.15.35",
    "@solana/wallet-adapter-react-ui": "^0.9.35",
    "@solana/wallet-adapter-wallets": "^0.19.32",
    "@solana/web3.js": "^1.95.4",
    "axios": "^1.6.8",
    "bs58": "^6.0.0",
    "next": "13.4.13",
    "react": "18.2.0",
    "react-dom": "18.2.0",
    "react-dropzone": "^14.2.3",
    "react-hot-toast": "^2.4.1",
    "react-icons": "^4.10.1"
  }
}

```

#### ENV.LOCAL

```
# PINATE KEYS
NEXT_PUBLIC_PINATA_AIP_KEY =
NEXT_PUBLIC_PINATA_SECRECT_KEY =

#  SHYFT
NEXT_PUBLIC_SHYFT_AIP_KEY =
NEXT_PUBLIC_SHYFT_ENDPOINT = https://api.shyft.to/sol/v1/
NEXT_PUBLIC_NFT_MARKETPLACE =

# MAINNET RPC URL
NEXT_PUBLIC_MAINNET_PRC_URL = https://solana-mainnet.g.alchemy.com/v2/M_Vs3I53rHZDrLMQUVQ-DMqA1HsyuB_w



#FORMSPREE
NEXT_PUBLIC_FORMSPREE_API  =


# ADMIN
NEXT_PUBLIC_ADMIN =
NEXT_PUBLIC_FEE = 0.005

# FEE CHARGE
NEXT_PUBLIC_RECEVIED_FEE =
NEXT_PUBLIC_NFT_BUY_FEE = 1
NEXT_PUBLIC_NFT_LISTING_FEE = 1


# TRANSACTION HAST 2kTdiZ4ejWT84nzbTqa1Wd6nfk9QJJrN5CiTBEegRth8Nk3mQJ3uWG2o2GaPFx8NCoehLAe1Ri6VsDy1YQ5x7pQK


```
