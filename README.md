# Description

[<img align="center" alt="NFTstorage" width="200px" src="https://camo.githubusercontent.com/1a0cf17dd0a19c4c4df2cfdff02eb4628f5ae35b7dd30dcd747b770ca1a2fb53/68747470733a2f2f6e66742e73746f726167652f696d616765732f6c6f676f2d6e66742e73746f726167652e737667" />][nftstorage]

Simple service to store data in a decentralized manner using _NFT Storage_ service.

[NFT Storage](https://nft.storage/) provides a simple API to uplaod up to 31 GB of data to IPFS.

More details can be found in their official [Documentation](https://nft.storage/docs/quickstart/)

# Installation

Clone the repository and run the following commands:

```shell
npm install
```

# Usage

To upload a file to IPFS run the following command:

```shell
node upload.mjs 'filename' 'short_description' 'long_description'
```

If the upload into IPFS was successful, the console will show something as follows:
```shell
Token {
  ipnft: 'bafyreifrkkhbwkf3fibwhbzcmpqnmh3b4t5t4ig7qdtymkdoatcycwe6n4',
  url: 'ipfs://bafyreifrkkhbwkf3fibwhbzcmpqnmh3b4t5t4ig7qdtymkdoatcycwe6n4/metadata.json'
}
```
