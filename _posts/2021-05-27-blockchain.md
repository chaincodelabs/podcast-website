---
title: "Chaincode Decoded: Blockchain"
tags:
  - blockchain
  - reorgs
  - mining theory
---

In this *Chaincode Decoded* segment we talk about the fundamental role of Bitcoin's blockchain and some of its pecularities.

<iframe src="TODO" height="102px" width="400px" frameborder="0" scrolling="no"></iframe>

[anchor.fm](#TODO-link-to-episode-14)

- Purpose of the blockchain (0:40)
- Mining is a lottery not a race (1:57)
- Why doesn't the same miner always win? (5:12)
- What happens if two blocks are found at the same height? (6:12)
- The longest reorgs (9:11)
- How does the blockchain work? (12:18)
  - Headers-first synchronization and Ultraprune: [Episode 1 with Pieter Wuille](https://podcast.chaincode.com/2020/01/27/pieter-wuille-1.html)
  - [Episode 5: The UTXO set](https://podcast.chaincode.com/2020/02/26/utxos-5.html)
- Why does Bitcoin converge on one chain? (15:20)
  - Selfish mining paper: [Majority is not Enough: Bitcoin Mining is Vulnerable](https://www.cs.cornell.edu/~ie53/publications/btcProcFC.pdf)
- Will we always find a new block? (18:04)
  - [Entropy sources in the block header](https://bitcoin.stackexchange.com/a/96442/5406)
- Mining pools have disjoint hashing spaces (19:30)
  - Correction: mining pools do not have a separate pay-out address for each participant, but give out a unique coinbase transaction stub for each.
  - [Eschaton block](https://twitter.com/orionwl/status/969903330523865088)

Thanks to [Caralie](https://twitter.com/CaralieCS/) for the sound engineering.
