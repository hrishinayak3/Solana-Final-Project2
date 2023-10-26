# SolanaBootcamp_FinalProject

## Overview

Welcome to the SolanaBootcamp_FinalProject! In this project, we have embarked on a creative journey to explore the world of Non-Fungible Tokens (NFTs) on the Solana Blockchain. Here, we'll introduce you to the key functionalities of our NFT smart contract and guide you through the build and deployment process.

## Project Highlights

This project revolves around the creation and management of NFTs through a meticulously crafted smart contract. Here are the core functionalities of our NFT smart contract:

### 1. Mint

The **Mint** instruction is at the heart of our NFT creation process. It plays a pivotal role in introducing new tokens into the Solana ecosystem. Through this instruction, we bring your artistic visions to life by generating unique NFTs. Key inputs, such as color, description, and rarity, guide the creation of gem metadata, resulting in the minting of your one-of-a-kind NFTs.

### 2. Transfer

The **Transfer** instruction empowers you to seamlessly send your tokens or NFTs from one Solana account to another. Whether you're trading, gifting, or simply sharing your digital art, this functionality makes it effortless and secure.

### 3. Burn

When the time comes to part ways with your tokens or NFTs, the **Burn** instruction comes into play. It allows you to gracefully retire your digital assets, removing them from circulation. This process ensures the integrity and rarity of your NFT collection.

## Getting Started

Now, let's dive into the practical aspects of this project:

### Build the Contract

Navigate to the program directory:

  ```shell
   cargo build-sbf
  ```


### Set Up Your Configuration

Ensure your configuration file is set to connect to the Solana Development Network (devnet) with the following command:

   ```shell
   solana config set --url devnet
   ```


### Build and Deploy the Contract

Build and deploy your smart contract. Don't forget to save the generated program ID for future reference.


### Download Dependencies

In the program_client directory, install the necessary dependencies by running:

    yarn install


### Additionally, include the Solana SPL Token library:

    yarn add @solana/spl-token


### Run the Application

Execute the application by running app.ts with your <YOUR_PROGRAM_ID>. This step will enable you to interact with your NFTs.


## Conclusion

The SolanaBootcamp_FinalProject is an exciting venture into the world of NFTs on the Solana Blockchain. With our NFT smart contract and the outlined instructions, you're well on your way to creating, managing, and sharing your unique digital assets.

We hope you find this project inspiring and educational. If you have any questions or need assistance, don't hesitate to reach out to me hrishinayak3@gmail.com . Happy Coding!
