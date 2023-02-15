---
title: "Greg Sanders - SIGHASH_ANYPREVOUT, ephemeral anchors and LN symmetry (ELTOO)"
tags:
  - SIGHASH_ANYPREVOUT
  - ephemeral anchors
  - Eltoo
  - LN symmetry
---
[Greg Sanders](https://twitter.com/theinstagibbs) joins us to discuss ANYPREVOUT, ephemeral anchors and LN symmetry (a.k.a. ELTOO).

<iframe src="https://anchor.fm/chaincode/embed/episodes/Greg-Sanders--SIGHASH_ANYPREVOUT--ephemeral-anchors-and-LN-symmetry-ELTOO---Episode-29-e1v1dc3" height="102px" width="400px" frameborder="0" scrolling="no"></iframe>

[anchor.fm](https://spotifyanchor-web.app.link/e/vHNeamxPrxb)

We cover:

- Package relay (2:07)

- [Pinning attacks](https://bitcoinops.org/en/topics/transaction-pinning/) (3:14)
  - CPFP 
  - [BIP125](https://github.com/bitcoin/bips/blob/master/bip-0125.mediawiki)
  - [T-Bast's pinning attack summary](https://github.com/t-bast/lightning-docs/blob/master/pinning-attacks.md)

- Mempool policy (4:56)

- Stuffing the mempool - 2017 (5:20)

- Rewrite mempool or make the problem simpler (07:57)

- [Package relay RBF](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2021-September/019464.html) A.K.A. V3 (8:38)

- Reducing the standard transaction size to 65 bytes [PR](https://github.com/bitcoin/bitcoin/pull/26265) (14:25)

- March to LN symmetry (19:07)

- [Daric: A Storage Efficient Payment Channel With Penalization Mechanism](https://eprint.iacr.org/2022/1295)
- [Two-party eltoo w/ punishment by AJ Towns](https://lists.linuxfoundation.org/pipermail/lightning-dev/2022-December/003788.html)

- [BIP118](https://github.com/bitcoin/bips/blob/master/bip-0118.mediawiki) - SIGHASH_ANYPREVOUT (26:17)
- [SIGHASH_NOINPUT](https://github.com/bitcoin/bips/commit/98b7238f68d17f0e01275dd32075078702225356?short_path=2f8c560#diff-2f8c560480095b9f314d3a7e17cf7048a10f9a15b391acaf2c96412d5b4d4b9c) 

- Softfork and activation history (28:11)
  - Author should be different than the champion 

- Ephemeral anchors (32:18)
  - [op_2 email from Luke](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2018-May/015945.html)
  - A business use case for ephemeral anchors

- Is ANYPREVOUT useful outside of LN symmetry? (43:27)