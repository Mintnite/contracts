## Intro
This repo contains the actual smart contract source code used at Mintnite.io.

## How to use
If you have deployed your smart contract, you may migrate your contract to another third-party contract interface such as MyEtherWallet. But you need to connect the actual wallet with the network that you used to deploy the contract and also include the ABI (Application Binary Interface) when interacting. The ABI files are named with .abi extension. NFT and SBT contracts share the same ABI so you will only probably find one .abi file for both contracts. For example, the ABI file for ERC721NFT.sol and ERC721SBT.sol is ERC721NFTSBT.abi

## Source code can be verified
When you deploy contracts on our platform, you could verify your contract source code with the code above. You may view some of the [verified contracts](https://mintnite.io/list-of-our-verified-smart-contracts-with-their-source-code) we performed.

