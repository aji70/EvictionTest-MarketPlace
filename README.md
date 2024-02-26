## MarketPlace sepolia contract address 0x4B0D79B5895DE901D0452eFb282Af03f9Af27813

## MarketPlaceToken sepolia contract address 0xd7D289d25302923F0fAA8599704aA144531B0eB8

Tested and worked effectively on remix you can check screenshots for proof of interaction, can be copied and pasted on remix, deploy with an nft address or better still load the address from sepolia an interact remember to pass value with the buy NFT function to purchase NFT successfully

NFT Marketplace Contract
This Solidity smart contract implements a basic NFT (Non-Fungible Token) marketplace where users can list their NFTs for sale and buy NFTs from other users.

Overview
The contract uses the OpenZeppelin ERC721 implementation for NFTs.
It includes functions to list an NFT for sale, buy an NFT, and retrieve listings.
Ether(Sepolia) is used as the payment method for buying and selling NFTs.
Deployment
Deploy the contract to a supported Ethereum network in my case it was sepolia
Pass the address of an existing ERC721 contract when deploying the NFTMarketplace contract.
Usage
Listing an NFT
Ensure you own the NFT you want to list.
Call the listNFT function with the token ID of your NFT and the price you want to sell it for.
Buying an NFT
Find an NFT listed for sale.
Call the buyNFT function with the token ID of the NFT you want to buy and the required payment.
Retrieving Listings
Use the getListing function with a token ID to check the details of a listing.
Use the getMyListedTokens function to retrieve a list of token IDs of NFTs you have listed for sale.
Development
The contract is written in Solidity version ^0.8.20.
Use the OpenZeppelin SafeMath library for arithmetic operations.
Ensure proper error handling and gas optimization in contract functions.
Future Improvements
Add additional features such as auctions, royalties, and metadata support.
Enhance the user interface for better usability and user experience.
Contributors
Ajidokwu Sabo
License
This project is licensed under the MIT License - see the LICENSE file for details.
