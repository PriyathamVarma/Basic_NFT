# Basic_NFT
![Hero Image](https://github.com/PriyathamVarma/Basic_NFT/blob/main/Diagrams/NFT%20(ERC-721%20token).jpg)
This repo is for showing basic implementation of NFTs(ERC-721 tokens) using openZeppelin


NFTs are unique and are owned by owners address. These can be used for real estate, voting rights and other self containing stuff. 

### Use of metadata

APIs for the NFT.

### Use of Enumerable

Check the balance of account on how many NFTs an account has.

### Use of URIStorage

Posibility to associate metadata to the NFTs.

The ERC721URIStorage contract is an implementation of ERC721 that includes the metadata standard extensions (IERC721Metadata) as well as a mechanism for per-token metadata. That’s where the _setTokenURI method comes from: we use it to store an item’s metadata.

### [Content Addressing](https://github.com/PriyathamVarma/Basic_NFT/tree/main/Content-addressing)

Content addressing is used to store the data file.

### Metadata schemas

NFTs are digital assets which represent images, videos, links, articles etc and the way we can do it is using through metadata. 

[Metadata](https://en.wikipedia.org/wiki/Metadata) is the data that provides information about other data but not the content of the data. In NFTs case, the metadata represnts the name, description, and other properties. 

> Why metadata standards are needed?

![metadata](https://github.com/PriyathamVarma/Basic_NFT/blob/main/Diagrams/NFT_1.drawio.png)

To make your NFT's compatible with market places and other platforms we need to follow the standards. [JSON Schema](https://json-schema.org/) is the standard adapted for JSON. 

> JSON for metadata

The most common format used for NFT metadata is [JSON](https://www.json.org/json-en.html). 

> Linking to NFT Assets

When linking from your metadata to another digital asset like an image file, we recommend storing the asset on IPFS and using an IPFS Uniform Resource Identifier (URI) to reference the asset. An IPFS URI is just the string ipfs:// followed by an IPFS CID (opens new window), for example: ipfs://bafybeigdyrzt5sfp7udm7hu76uh7y26nf3efuylqabf3oclgtqy55fbzdi.

## Prerequesties

- We need a smart contract to deploy the NFT tokens
- Solidity is the language of prefernce
- Service Provider Node - Alchemy, Infura
- Test tokens to pay gas fees


## Steps


## Important Links

- [Open Zeppelin](https://docs.openzeppelin.com/)
- [Best NFT site](https://nftschool.dev/)
- [NFT storage](https://nft.storage/#docs)
- [IPFS](https://docs.ipfs.tech/)
- [Opensea NFt standards](https://docs.opensea.io/docs/metadata-standards)
- [Chainlink NFT standards](https://blog.chain.link/build-deploy-and-sell-your-own-dynamic-nft/)


## Tools

- [Wizard](https://docs.openzeppelin.com/contracts/4.x/wizard)
