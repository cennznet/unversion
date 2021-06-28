# UNversion
A Version System for dApp and other data.

# Create something UNversioned
To create something that is UNversion you simply create a new collection. [Introducing the CENNZnet NFT Module](https://medium.com/centrality/introducing-the-cennznet-nft-module-c1ce3ed79840) [Wiki Reference](https://wiki.cennz.net/#/CENNZnet-API/NFT-API?id=createcollectionname-collectionnametype-metadata_base_uri-optionltmetadatabaseurigt-royalties_schedule-optionltroyaltiesschedulegt)

<img width="1277" alt="Screen Shot 2021-06-28 at 2 28 57 PM" src="https://user-images.githubusercontent.com/1079931/123570916-4482b500-d81d-11eb-85dc-b361c3208b6a.png">


https://user-images.githubusercontent.com/1079931/123570889-37fe5c80-d81d-11eb-8270-836c97f5f473.mov

[Example on UNcover](https://uncoverexplorer.com/extrinsic/0x37eb0b373478bfd00c3c6fb5cbb2a2ad2b9e4315d8a159c5e8760bb182f802ea)

# Create a new version
To create a new version simply mint a new NFT in this collection, the first attribute is use [https://semver.org](https://semver.org). 
Usually I like to host everything in IPFS but the binary or source can be host anywhere

| Index | Name | Type | Example |
|-------|------|------|---------|
| 0 | Version | Text | 0.0.1 |
| 1 | Binary | Url | ipfs://somewhere |
| 2 | Change Log | Text | First Commit |
| 3 | Source | Url | ipfs://somewhere |


<img width="1262" alt="Screen Shot 2021-06-28 at 2 46 17 PM" src="https://user-images.githubusercontent.com/1079931/123572080-a0e6d400-d81f-11eb-8cd1-7a06d380d873.png">
