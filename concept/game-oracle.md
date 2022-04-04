# Game Oracle

### What is an oracle in a blockchain? <a href="#header-0" id="header-0"></a>

Blockchain oracles are third-party services that provide smart contracts with external information. They serve as bridges between blockchains and the outside world. Blockchains and smart contracts cannot access off-chain data (data that is outside of the network). However, for many contractual agreements, it is vital to have relevant information from the outside world to execute the agreement.

This is where blockchain oracles come into play, as they provide a link between off-chain and on-chain data. Oracles are vital within the blockchain ecosystem because they broaden the scope in which smart contracts can operate. Without blockchain oracles, smart contracts would have very limited use, as they would only have access to data from within their networks.&#x20;

It’s important to note that a blockchain oracle is not the data source itself, but rather the layer that queries, verifies, and authenticates external data sources and then relays that information. The data transmitted by oracles comes in many forms – price information, the successful completion of a payment, or the temperature measured by a sensor.&#x20;

To call data from the outside world, the smart contract has to be invoked, and network resources have to be spent. Some oracles also have the ability to not only relay information to smart contracts, but to send it back to external sources.

Many different types of oracles exist – how a blockchain oracle operates is entirely dependent on what it is designed for.

### What is Chainlink?

Chainlink decentralized oracle networks provide tamper-proof inputs, outputs, and computations to support advanced smart contracts on any blockchain.



## What is VRF in Chainlink?&#x20;



For each request, Chainlink VRF generates one or more random values and cryptographic proof of how those values were determined. The proof is published and verified on-chain before any consuming applications can use it. This process ensures that results cannot be tampered with or manipulated by any single entity including oracle operators, miners, users, or smart contract developers.

Use Chainlink VRF to build reliable smart contracts for any applications that rely on unpredictable outcomes:

* Building blockchain games and NFTs.

We use VRF to prove who can access the function (mint token) with VRF, and the signature out of the chain allows the player to receive their prize.

\
