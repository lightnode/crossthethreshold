# Cross The Threshold
## Create a canonical Ethereum to Base NFT Bridge

1. autodeploy a corresponding NFT contract on Base if _remoteToken is left empty
2. copy tokenURI of mainnet NFT to Base NFT
3. mirror the royalty info and make sure it's set to something on Base that you can acquire


### References
- OP721 - https://github.com/ethereum-optimism/optimism/blob/develop/packages/contracts-bedrock/src/universal/OptimismMintableERC721.sol
- OP721Factory - https://github.com/ethereum-optimism/optimism/blob/develop/packages/contracts-bedrock/src/universal/OptimismMintableERC721Factory.sol
- Warpcast Thread - https://warpcast.com/jessepollak/0x805493e9
