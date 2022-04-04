<p align="center"><img src="https://github.com/OffchainLabs/arbitrum/blob/master/docs/assets/offchain_labs_logo.png" width="600"></p>

# Important Info

This package requires a NVMe drive or faster. Syncing takes at least 2 days on an NVMe. A node reboot requires you to run through most of the state in the DB again. There is also no fast sync mode. When Arbitrum Nitro is released, it should be akin to running a normal geth node. But until then, this is what we have.

# Used Ports

| Port | Used For |
| ---- | -------- |
| 8547 | JSON-RPC |
| 8548 | WebSocket|

# Arbitrum Mainnet Beta Node

This DAppNode package uses the official Arbitrum Go Node. 

Arbitrum is a Layer 2 cryptocurrency platform that makes smart contracts scalable, fast, and private. Arbitrum interoperates closely with Ethereum, so Ethereum developers can easily cross-compile their contracts to run on Arbitrum. Arbitrum achieves these goals through a unique combination of incentives, network protocol design, and virtual machine architecture. Arbitrum has three modes: channels, AnyTrust sidechains, and rollup. Channels and sidechains provide the AnyTrust Guarantee which ensures that the code will run correctly as long as any validator is honest.

# License

This repository is offered under the Apache 2.0 license. See LICENSE for details.