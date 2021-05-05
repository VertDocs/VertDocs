## How do I mine?
Nearly any computer with a modern graphics card can easily mine using the [Vertcoin One-Click Miner (OCM)](https://github.com/vertcoin-project/one-click-miner-vnext/releases/latest). The OCM features a built-in Vertcoin wallet and is a wrapper for the commandline based [VerthashMiner](https://github.com/CryptoGraphics/VerthashMiner) which will yield the same hashrate. CPU mining is not recommended and will yield a very low hashrate compared to GPU.

## What is Mining?
The Vertcoin system of trust is based on global computation. Transactions are bundled into blocks, which require an enormous amount of computation to prove, but only a small amount of computation to verify as proven. The mining process serves two purposes in Vertcoin: `[1]`

1. Mining nodes validate all transactions by reference to Vertcoin’s consensus rules. Mining provides security for vertcoin transactions by rejecting invalid or malformed transactions.

2. Mining creates new vertcoin in each block, almost like a central bank printing new money. The amount of vertcoin created per block is limited and diminishes with time, following a fixed issuance schedule.

## Why do we need Miners?
New transactions flow into the network from user wallets and other applications. As these are seen by the vertcoin network nodes, they are added to a temporary pool of unverified transactions maintained by each node known as the memory pool. As miners construct new blocks, they add unverified transactions from the memory pool to the new block and then attempt to prove the validity of that new block, with the mining algorithm (Proof-of-Work). `[2]`

Mining achieves a fine balance between cost and reward. Mining uses electricity to solve a mathematical problem. A successful miner will collect a reward in the form of new vertcoin and transaction fees. The reward can only be collected if the miner has correctly validated all the transactions, to the satisfaction of the rules of consensus. This delicate balance provides security for vertcoin without a central authority. `[1]`

## Prerequisite Information
Vertcoin currently uses the Verthash hashing algorithm created to maintain ASIC resistance, along with this hashing algorithm the community enforces a mutually held social contract to fork when ASICs are introduced. Vertcoin is against the monopolization of special mining hardware allowing consumer-grade electronics to act as the securing force for the blockchain. Vertcoin has developed it's One-Click Miner to reduce the technical barrier of entry for mining Vertcoin.

## References
`[1] Mastering Bitcoin 2nd Edition - Bitcoin Mining - https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch02.asciidoc#bitcoin-mining`  
`[2] Mastering Bitcoin 2nd Edition - Mining Transactions in Blocks - https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch02.asciidoc#mining-transactions-in-blocks`
