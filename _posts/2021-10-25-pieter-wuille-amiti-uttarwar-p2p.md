---
title: "Pieter Wuille & Amiti Uttarwar and the P2P network"
tags:
  - p2p
  - eclipse attacks
  - addrMan
  - addrRelay
---

P2P experts Pieter and Amiti chat about the P2P network.

<iframe src="https://anchor.fm/chaincode/embed/episodes/Amiti-Uttarwar-and-the-P2P-network---Episode-15-e18v7oq" height="102px" width="400px" frameborder="0" scrolling="no"></iframe>

[anchor.fm](https://anchor.fm/chaincode/episodes/Amiti-Uttarwar-and-the-P2P-network---Episode-15-e18v7oq)

Pieter and Amiti discuss:

- AddrRelay high-level goals and constraints (1:15)
  - Very different than the goals of blocks and transactions
  - Marginal fee rate (4:35)

- Should we consider different transport layers? (5:40)
  - [FIBRE Episode with Matt Corallo](https://podcast.chaincode.com/2020/03/12/matt-corallo-6.html) (7:40)

- The inroduction of Addrman in 2012, [PR #787](https://github.com/bitcoin/bitcoin/pull/787) (8:55)
  - What existed before AddrMan and the evolution of DoS resistance.

- Eclipse Attack paper (14:55)
  - [Sybil attack](https://en.wikipedia.org/wiki/Sybil_attack)
  - [Addrman and eclipse attacks wiki page](https://github.com/bitcoin-core/bitcoin-devwiki/wiki/Addrman-and-eclipse-attacks)
  - [Anchors connections - PR #17428](https://github.com/bitcoin/bitcoin/pull/17428)

- [Connection exhaustion issue](https://github.com/bitcoin-core/bitcoin-devwiki/wiki/Addrman-and-eclipse-attacks#open-questions-and-areas-for-research) (19:50)

- Erlay ([paper](https://arxiv.org/abs/1905.10518), [BIP](https://github.com/naumenkogs/bips/blob/bip_0330_updates/bip-0330.mediawiki) (20:55)

- AddrRelay (23:15)
  - [Limiting blackholes PR]()
  - [Rate limiting on address gossip in 22.0]() ()
    - [Leaky bucket rate limiter]() (27:00)

- Address Spam (29:20)

- Mateos Clinkman? 9 min in the future timestamp
  - 3135 - paper - who is the author?()
  - how many peers is this public node connected to?
  - [Coin Scope paper]() (31:45)
  - [TxProbe]() (32:00)

- Seperate network stack (37:20)

- Fingerprint attacks (37:15)

- [ASMAP]() (39:00)

Thanks to [Caralie](https://twitter.com/CaralieC/) for the sound engineering.
