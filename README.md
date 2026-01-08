Blockchain-Powered NFT Marketplace

A decentralized Web3 marketplace that allows users to mint, discover, list, and buy NFTs through seamless wallet integration and smart contract interactions.

Features

Mint NFTs using deployed Solidity smart contracts

List owned NFTs for sale on the marketplace

Buy NFTs via wallet-signed blockchain transactions

Discover available NFTs on a dedicated Discover page

View owned NFT collection using React Router navigation

Responsive and modular NFT card UI with UX-focused styling

Tech Stack

Frontend: React.js, React Router DOM

Blockchain: Solidity Smart Contracts

Web3 Integration: Ethers.js / Web3 Provider (MetaMask, RPC)

Styling: Modern responsive UI/UX

Workflow Overview

Connect wallet (MetaMask)

Mint NFT → contract call → wait for confirmation

View owned NFTs (fetched from blockchain provider)

List NFT for sale (writes listing data on-chain)

Buy NFT → approval → transaction → success state UI

Installation
git clone <repository-url>
cd <project-folder>
npm install
npm start

Smart Contract Notes

Smart contracts act as the decentralized backend logic for minting, ownership, sale listings, and purchases.

All transactions are signed and sent through the connected wallet.

Future Enhancements

Add ranking and rating for active traders

Implement bot interactions for testing marketplace flow

Introduce filters for NFT discovery
