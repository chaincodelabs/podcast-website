---
title: "Pieter Wuille & Amiti Uttarwar and the P2P network"
tags:
  - p2p
  - eclipse attacks
  - addrMan
  - addrRelay
---

P2P experts Pieter and Amiti chat about the P2P network.

<iframe src="https://anchor.fm/chaincode/embed/episodes/Pieter-Wuille--Amiti-Uttarwar-and-the-P2P-network---Episode-16-e19bgv7" height="102px" width="400px" frameborder="0" scrolling="no"></iframe>

[anchor.fm](https://anchor.fm/chaincode/episodes/Pieter-Wuille--Amiti-Uttarwar-and-the-P2P-network---Episode-16-e19bgv7)

Pieter and Amiti discuss:

- AddrRelay high-level goals and constraints (1:15)
  - Very different than the goals of blocks and transactions
  - Marginal fee rate (4:35)

- Should we consider different transport layers? (5:40)
  - [FIBRE Episode with Matt Corallo](https://podcast.chaincode.com/2020/03/12/matt-corallo-6.html) (7:40)

- The introduction of Addrman in 2012, [PR #787](https://github.com/bitcoin/bitcoin/pull/787) (8:55)
  - What existed before AddrMan and the evolution of DoS resistance.

- [Eclipse Attack paper](https://eprint.iacr.org/2015/263.pdf) (14:55)
  - [Sybil attack](https://en.wikipedia.org/wiki/Sybil_attack)
  - [Addrman and eclipse attacks wiki page](https://github.com/bitcoin-core/bitcoin-devwiki/wiki/Addrman-and-eclipse-attacks)
  - [Anchors connections - PR #17428](https://github.com/bitcoin/bitcoin/pull/17428)

- [Connection exhaustion issue](https://github.com/bitcoin-core/bitcoin-devwiki/wiki/Addrman-and-eclipse-attacks#open-questions-and-areas-for-research) (19:50)

- Erlay ([paper](https://arxiv.org/abs/1905.10518), [BIP](https://github.com/naumenkogs/bips/blob/bip_0330_updates/bip-0330.mediawiki)) (20:55)

- AddrRelay (23:15)
  - [Limiting addr black holes - PR #21528](https://github.com/bitcoin/bitcoin/pull/21528)
  - [Rate limiting on address gossip in 22.0](https://github.com/bitcoin/bitcoin/pull/22387)
    - [Leaky bucket rate limiter](https://en.wikipedia.org/wiki/Leaky_bucket) (27:00)

- Address Spam (29:20)
  - [Estimating the Node Degree of Public Peers and Detecting Sybil Peers Based on Address Messages in the Bitcoin P2P Network](https://arxiv.org/abs/2108.00815) by Matthias Grundmann (31:35)
  - [Coinscope paper](https://www.cs.umd.edu/projects/coinscope/coinscope.pdf) (31:45)
  - [TxProbe](https://arxiv.org/abs/1812.00942) (32:00)

- Separate network stack (37:20)

- Fingerprint attacks (37:15)

- [ASMAP](https://blog.bitmex.com/call-to-action-testing-and-improving-asmap/) (39:00)

Thanks to [Caralie](https://twitter.com/CaralieC/) for the sound engineering.
