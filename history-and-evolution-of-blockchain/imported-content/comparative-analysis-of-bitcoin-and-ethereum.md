# Comparative Analysis of Bitcoin and Ethereum

> **Images rule:** Images go in the `images/` folder and are embedded here with Markdown, for example `![Diagram](images/diagram.png)`. Use PNG or JPG. External links (Google Drive, Canva, slides) are extras only: they are not marked unless the same content is also in this README.

## Bitcoin

Bitcoin is the pioneer of blockchain technology and as such it is the most well-known cryptocurrency. Its design enables it to function as a decentralized digital currency, allowing for peer-to-peer transactions without the need for a central authority.

**How proof of work works:** Proof of work is a consensus where miners compete to solve complex mathematical puzzles. The first miner to solve the puzzle gets to add a new block and receives newly minted bitcoins and transaction fees. The security behiind bitcoins proof of work is highly secure due to the amount of computational required to attack the network, but it also leads to high energy consumption which is a major concern.

**Bitcoin's main use cases:**

* **Store of value:** Many investors hold Bitcoin as a long-term investment and it is often seen as a digital gold due to its limited supply of 21 million coins and because of this its design enables it to function as a hedge against inflation and a store of value in times of economic uncertainty.
* **Digital currency:** Bitcoin is used for transactions and remittances, especialy in countries with unstable currencies or limited access to traditional banking systems. Due to this design it also enables it to function as a peer-to-peer electronic cash system that can be used to send money to anyone, anywhere in the world, without the need for a bank or other financial institution.

## Ethereum

Ethereum was developed in 2015 as a decentralized platform that enables the creation of smart contracts and decentralized applications (dapps). It is the most popular platform for dapps and has a large ecosystem of developers and users. In September 2022, Ethereum successfully transitioned from proof of work to proof of stake in an event known as the Merge, which significantly reduced its energy consumption and improved its scalability.

**How proof of stake works:** Proof of stake is a consensus mechanism that allows validators to prove that they have put something of value (stake) in the network. In Ethereum's proof of stake, validators explicitly stake their own ETH in a smart contract. The validator is then responsible for attesting to the validity of transactions and proposing new blocks. If the validator acts maliciously, their stake can be destroyed, this is known as slashing.

**Ethereum's main use cases:**

* **Dapps:** Ethereum is a decentralized platform that enables the creation of smart contracts and decentralized applications (dapps). Developers use Ethereum to create dapps that can be used for a variety of purposes, such as gaming, finance, and social media. Due to its smart contracts, dapps can automate complex transactions and agreements without the need for intermediaries.
* **DeFi:** Decentralized finance, or DeFi, refers to financial services that are built on blockchain technology. Ethereum is the leading platform for DeFi applications, with a large ecosystem of developers and users. Smart contracts enable the creation of a wide range of DeFi applications, such as lending, borrowing, and trading platforms and with mechanisms such as non-custodial escrows, deterministic execution of financial agreements and the removal of intermediaries, DeFi aims to recreate traditional financial systems in a decentralized manner.
* **NFTs:** NFTs, or non-fungible tokens, are digital assets that are unique and cannot be replaced with another identical asset. They are used to represent ownership of digital or physical assets, such as art, collectibles, and virtual real estate. Smart contracts enable the creation of NFTs by providing a way to prove unique ownership of digital assets in a transparent and immutable way via a cryptographic address.

## Comparison

| Dimension                         | Bitcoin                          | Ethereum               |
| --------------------------------- | -------------------------------- | ---------------------- |
| Consensus mechanism               | Proof of Work                    | Proof of Stake         |
| Energy use                        | High                             | Low                    |
| Main use cases                    | Digital currency, store of value | dapps, DeFi, NFTs      |
| Market capitalisation (with year) | $1.64 trillion (2026)            | $293.19 billion (2026) |
| Adoption                          | High                             | Medium                 |

## Market position over time

Bitcoin and Ethereum have consistently occupied the top two spots in the cryptocurrency ecosystem:

* **Bitcoin (Rank #1):** Since its inception in 2009, Bitcoin has maintained the #1 rank by market capitalization. As of October 2026, Bitcoin's price is approximately $81,900 with a market capitalization of $1.64 trillion. It has a circulating supply of \~20.09 million BTC toward its fixed maximum cap of 21 million BTC. A primary trend driving Bitcoin's market position is deep institutional adoption via spot ETFs, corporate treasury allocations, and macro asset integration.
* **Ethereum (Rank #2):** Since rising above early altcoins in 2016, Ethereum has maintained the #2 market position. As of October 2026, Ethereum trades around $2,299 with a market capitalization of $293.19 billion and a circulating supply of \~122.14 million ETH (with no arbitrary supply ceiling, but an issuance rate balanced by EIP-1559 transaction fee burns).
* **Evolving Trends:** On the Ethereum roadmap, the network is progressing through upcoming upgrades such as **Glamsterdam** (targeted for late 2026), focusing on cheaper transaction data availability, improved user experience (account abstraction), privacy enhancements, and post-quantum cryptography research.

As of today (19 October 2026) Bitcoin's market capitalisation is $1.64 trillion and Ethereum's is $293.19 billion. Bitcoin's market capitalisation has grown steadily since its creation in 2009, while Ethereum's market capitalisation has grown more rapidly since its creation in 2015. Bitcoin's market capitalisation is larger than Ethereum's, but Ethereum's market capitalisation is growing more rapidly. This is likely because Ethereum is a newer technology and has more potential for growth. Bitcoin has a total supply of 20.09M BTC with a max supply of 21M BTC and Ethereum has a total supply of 122.14M ETH with a max supply of infinity. Bitcoin's price is around $81,900 and Ethereum's price is around $2,400. ([https://coinmarketcap.com](https://coinmarketcap.com/))

The new trend for Ethereum is Glamsterdam, which makes space for cheaper tranactions, extra security, better user experience and privacy by default with hopes of post quantum security. ([https://ethereum.org/roadmap/](https://ethereum.org/roadmap/))

## Analysis and conclusion

While Bitcoin and Ethereum are frequently compared as rival cryptocurrencies, they optimize for fundamentally different goals.

**Similarities:**\
Both networks are permissionless, public, decentralized blockchains that operate over peer-to-peer gossip networks without centralized intermediaries. Both rely on cryptographic public-key infrastructure (secp256k1 elliptic curves) for address ownership and transaction authentication, maintain immutable transaction histories, and resolve the Byzantine Generals Problem through economic consensus.

**Differences & Non-Obvious Conclusions:**

{% stepper %}
{% step %}
## Specialization vs. Generalization

A non-obvious conclusion is that Bitcoin and Ethereum are not zero-sum competitors; they occupy different layers of the digital economy. Bitcoin deliberately prioritizes protocol ossification, minimalism, and backward compatibility to ensure that its monetary rules never change, optimizing it as a pure monetary base layer ("digital gold"). In contrast, Ethereum prioritizes continuous protocol evolution and modular scaling (Layer 1 for settlement, Layer 2 rollups for execution), optimizing it as a decentralized world computer.
{% endstep %}

{% step %}
## Monetary Architecture (Fixed Scarcity vs. Utility-Driven Deflation)

While Bitcoin enforces scarcity through an absolute programmatic limit of 21 million coins, Ethereum's monetary policy is dynamic. Through EIP-1559 and Proof of Stake, base transaction fees are burned rather than given to validators. Consequently, during periods of high on-chain economic activity, Ethereum can become deflationary, directly coupling the asset's scarcity to platform adoption rather than a fixed issuance schedule.
{% endstep %}
{% endstepper %}

**Justified View on Future Trajectory:**\
Although Ethereum offers greater technological programmability and underpins the decentralized Web3 economy, Bitcoin will likely retain its market capitalization lead as the primary global reserve asset. Institutional capital and conservative financial institutions prioritize Bitcoin's immutable, unchangeable rules and lack of governance overhead. Meanwhile, Ethereum will dominate active economic utility, transaction frequency, and digital commerce settlement across decentralized finance.

## References

1. Ethereum Foundation. (n.d.). _Ethereum Virtual Machine (EVM)_. Ethereum.org. Retrieved October 19, 2026, from https://ethereum.org/developers/docs/evm/
2. Ethereum Foundation. (n.d.). _Proof-of-Stake (PoS)_. Ethereum.org. Retrieved October 19, 2026, from https://ethereum.org/developers/docs/consensus-mechanisms/pos/
3. Frankenfield, J. (2024). _Proof of Work (PoW): How It Works in Blockchain and Crypto_. Investopedia. Retrieved October 19, 2026, from https://www.investopedia.com/terms/p/proof-work.asp
4. CoinMarketCap. (2026). _Bitcoin (BTC) Price, Charts, and Market Cap_. Retrieved October 19, 2026, from https://coinmarketcap.com/currencies/bitcoin/
5. CoinMarketCap. (2026). _Ethereum (ETH) Price, Charts, and Market Cap_. Retrieved October 19, 2026, from https://coinmarketcap.com/currencies/ethereum/
6. Ethereum Foundation. (2026). _Ethereum Roadmap_. Ethereum.org. Retrieved October 19, 2026, from https://ethereum.org/roadmap/
