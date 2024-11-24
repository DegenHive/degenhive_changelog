## DegenHive Mainnet Addresses and Object IDs

This repository stores mainnet addresses and object IDs for packages and objects which implement DegenHive on the Sui Network.

## Package Upgrade History

### Core Package
| Date | Package Name | Address | Transaction Hash | Version |
|---------|---------|------------|-----------------|------|
| Nov 14, 2024  |DRAGON FOOD | 0x9a6a2041576d996414723481c68ea60e92754906f7770f78646870039eb387be     | [TxLink](https://suivision.xyz/txblock/Bf7SHm3bS6ehmLiFFSUm8pRNT9SJoVJXH2jfHRRqgwj)  | 2 |
| Nov 24, 2024  |MEME LAUNCHPAD | 0x2b9b0ba3d4efca53a2cbe669cd95d3c169fa3d2e889d2806279c339f51610a86     | [TxLink](https://suivision.xyz/txblock/4VHPgFx9kNBE45YZVgSLoetqVJcjoPZsAXA7wsaTrPVy)  | 4 |


## Latest Package Addresses

| Package Name | Address | Description |
|-------------|----------|-------------|
| Yield Flow        | 0x50c2216a078d3bdf5081fe436df9f42dfdbe538ebd9c935913ce2436362cff90    | Implements protocol configuration related logic |
| AMM Math   | 0x6c442d664dffc25e3fda48f15370ffaecac1f94ecb6debb46cd41ac4b38bddfa    | Implenents Stableswap, weighted and curved AMM pools math |
| DSUI Vault   | 0x53578180d93e5fa7b10334045c4565e3c743f0eb64c89932b14adb1b0baab145    | Implements SUI liquid staking via DSUI VAULT |
| Dragon Trainer   | 0x84f8a4ed68568c4f30592d03dfcaf7bedcae27e3a1e84a1ba7dfd4886c511cbc    | Implements Dragon Trainer, dragon-bees and marketplace logic |
| Two Token AMM   | 0x1609ad341cc5ef030d782ee7c2d84070d0768c6cede910e216c3ff1873a84bc1    | Implements Two Token AMM |
| Three Token AMM   | 0xb0e95627dfee7e43bb8d119f6a63abd4cbbc8f8abc17d403844e47244bd91e67    | Implements Three Token AMM |
| Dragon Food   | 0x9a6a2041576d996414723481c68ea60e92754906f7770f78646870039eb387be    | Implements LP token staking for rewards |
| Queen Maker   | 0x83ba940faec75a014752518940e225d0f150b439068af0ef9e36fba1a20a372d    | Implements Queen Maker |
| Scripts   | 0x950cafef35150568f2b7b9b5cb911656dc5b18ffa1b60fcb8263b2845b3dc0b9    | Implements helper router functions for our AMM pools |
| Meme Launchpad   | 0x2b9b0ba3d4efca53a2cbe669cd95d3c169fa3d2e889d2806279c339f51610a86    | Implements Meme Launchpad |
| Vesting   | 0xff2cfa3438beb90b23b6783f7c0dced77ba4f69bd2c084e70b6870aa260b4129    | Implements Vesting for early backers and team |




## Shared Objects

| Object Name | Address | Link | Description |
|-------------|---------|------|-------------|
| TWO POOL REGISTRY | 0xefd672db3df3885a8745803f0ede200402dba2e8cecea9bf62ce7a411e004a5d | [Link](https://suivision.xyz/object/0xefd672db3df3885a8745803f0ede200402dba2e8cecea9bf62ce7a411e004a5d) | Required when creating a new 2-token AMM pool. Stores 2-token AMM pool addresses <> identifiers mapping |
| THREE POOL REGISTRY | 0xb7c5c13c91397d411ba3dbba36505b9e843885e5c2ed00cf6ba235890d9a8af5 | [Link](https://suivision.xyz/object/0xb7c5c13c91397d411ba3dbba36505b9e843885e5c2ed00cf6ba235890d9a8af5) | Required when creating a new 3-token AMM pool. Stores 3-token AMM pool addresses <> identifiers mapping |  
| DSUI VAULT | 0x85aaf87a770b4a09822e7ca3de7f9424a4f58688cfa120f55b294a98d599d402 | [Link](https://suivision.xyz/object/0x85aaf87a770b4a09822e7ca3de7f9424a4f58688cfa120f55b294a98d599d402) | Implements DSUI Vault (SUI liquid staking) |
| BEES MANAGER     | 0x633a531eefd24c23219716efb413a726fb9a244d4196d1432e6152af1fbe50ac   | [Link](https://suivision.xyz/object/0x633a531eefd24c23219716efb413a726fb9a244d4196d1432e6152af1fbe50ac) | Manages the dragon-bees NFT collection |
| YIELD FARM     | 0x4070fd06a34ec576ef7185ff45679233ceb39a7e03473ccbb3a4a60728cceffb   | [Link](https://suivision.xyz/object/0x4070fd06a34ec576ef7185ff45679233ceb39a7e03473ccbb3a4a60728cceffb) | Custodies HIVE and HONEY LP tokens to be distributed among dragon-bee NFTs |
| TRAINER_MAPPING_STORE     | 0xc37f21db36c0a5d675a6864f21f0935a83952ade00e46b84195be4434e9c402b   | [Link](https://suivision.xyz/object/0xc37f21db36c0a5d675a6864f21f0935a83952ade00e46b84195be4434e9c402b) | Stores dragon-trainers <> usernames and similar mappings for quicker access |
| MARKETPLACE     | 0x8714e3aa8c2ae421420997a520b38a8bf66965acc9c130246437b14cd1bbb924   | [Link](https://suivision.xyz/object/0x8714e3aa8c2ae421420997a520b38a8bf66965acc9c130246437b14cd1bbb924) | Facilitates dragon-bees trading among users |
| QUEEN MAKER     | 0xf8fe8b500c206044d1a46797ca268cf65154729d32255fcbaa149b3ddd4780f7   | [Link](https://suivision.xyz/object/0xf8fe8b500c206044d1a46797ca268cf65154729d32255fcbaa149b3ddd4780f7) | Implements auction logic for a dragon-bee to become a queen-bee |
| DRAGON FOOD     | 0x8c4452801b68f4d22f5cec0f96562bc1ba7f93e28377f19ac9d0ec8814089dc3   | [Link](https://suivision.xyz/object/0x8c4452801b68f4d22f5cec0f96562bc1ba7f93e28377f19ac9d0ec8814089dc3) | Implements LP token staking for rewards |
| HONEY MANAGER     | 0x21fbea0ca478ca51a00766529ebcf5f0eded1d4a9fcbd81f7cba48fa5744674a   | [Link](https://suivision.xyz/object/0x21fbea0ca478ca51a00766529ebcf5f0eded1d4a9fcbd81f7cba48fa5744674a) | Required for txs involving HONEY token |
| MEME LAUNCHPAD     | 0xd9c4a9a46e00dde933d31ebfb66f657c13e0efcb9cc99a60785289af11268559   | [Link](https://suivision.xyz/object/0xd9c4a9a46e00dde933d31ebfb66f657c13e0efcb9cc99a60785289af11268559) | Implements Meme Launchpad for launching new tokens on DegenHive |
| VESTING VAULT     | 0x0ab64ecf6dfd9d92221f9655c03b551ae795a76a996583235faf6b12a9c20375   | [Link](https://suivision.xyz/object/0x0ab64ecf6dfd9d92221f9655c03b551ae795a76a996583235faf6b12a9c20375) | Implements vesting for early backers and team |
| YIELD FLOW OBJECT     | 0x5a79f26a90cf6a652cf45ad3dfbe1e3565503e70d866e3149292ccbc8fcd1420   | [Link](https://suivision.xyz/object/0x5a79f26a90cf6a652cf45ad3dfbe1e3565503e70d866e3149292ccbc8fcd1420) | Implements protocol configuration related logic |
| SUI FEE COLLECTOR     | 0x641176d85a5275c2f61e2980defbed0351e9fc37acf356de87cc5336ccb167d9   | [Link](https://suivision.xyz/object/0x641176d85a5275c2f61e2980defbed0351e9fc37acf356de87cc5336ccb167d9) | Collects SUI to be distributed among dragon-bees |
| HIDDEN WORLD     | 0x6eaa19716aa30990e67cd8928a8ec0ccd35f790027a3ff49ee17a89b00b580a7   | [Link](https://suivision.xyz/object/0x6eaa19716aa30990e67cd8928a8ec0ccd35f790027a3ff49ee17a89b00b580a7) | Implements Hidden World (p2p battles b/w dragon-bees) |
| TWAP UPDATE CAP     | 0x3a2c03d580b574618e2e5a99dc4060c1614fa7e92279e80977f4c8cbec0a42a9   | [Link](https://suivision.xyz/object/0x3a2c03d580b574618e2e5a99dc4060c1614fa7e92279e80977f4c8cbec0a42a9) | Required for txs involving HIVE TWAP oracle |
| HIVE GRAPH     | 0x25706d8493025282679e4f161d3900237e9a72ba172d4753a9bc44d89c51adf4   | [Link](https://suivision.xyz/object/0x25706d8493025282679e4f161d3900237e9a72ba172d4753a9bc44d89c51adf4) | Implements follow / unfollow logic b/w dragon-trainers |



## Token related Objects

| Object Name | Address | Link | Description |
|-------------|---------|------|-------------|
| HONEY TOKEN POLICY | 0x4bf2edc90330aadd6f6b61f4d6bc0f7c49a53da9afe5e60cd4aee438324eb316 | [Link](https://suivision.xyz/object/0x4bf2edc90330aadd6f6b61f4d6bc0f7c49a53da9afe5e60cd4aee438324eb316) | Required for txs involving HONEY token |
| DSUI METADATA | 0xd80bc68ffcd2774d158e45f3aff6626b52cfc2bbb50fe65b5bb8baeb2d0d881f | [Link](https://suivision.xyz/object/0xd80bc68ffcd2774d158e45f3aff6626b52cfc2bbb50fe65b5bb8baeb2d0d881f) | Metadata for DSUI token |
| HONEY METADATA | 0x9c51399d3738ea35cc40cefe477837202669975fcc0a20874c88049e97fa45dc | [Link](https://suivision.xyz/object/0x9c51399d3738ea35cc40cefe477837202669975fcc0a20874c88049e97fa45dc) | Metadata for HONEY token |
| HIVE METADATA | 0x21e4cbdea2e2784b11c98ba65467be8e1f31e0e55468b9bdd703ac6d87f2e8fc | [Link](https://suivision.xyz/object/0x21e4cbdea2e2784b11c98ba65467be8e1f31e0e55468b9bdd703ac6d87f2e8fc) | Metadata for HIVE token |
 