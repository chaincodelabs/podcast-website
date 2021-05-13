---
title: "Matt Corallo and LDK"
tags:
  - Lightning Development Kit
  - Lightning
  - Rust-lightning
---

In Episode 13, we sit down again with [Matt Corallo](https://twitter.com/TheBlueMatt) and discuss his work on the [Lightning Development Kit](https://lightningdevkit.org/) (LDK).

<iframe src="https://anchor.fm/chaincode/embed/episodes/Matt-Corallo-and-Lightning-Development-Kit---Episode-13-e10qin2" height="102px" width="400px" frameborder="0" scrolling="no"></iframe>

[anchor.fm](https://anchor.fm/chaincode/episodes/Matt-Corallo-and-Lightning-Development-Kit---Episode-13-e10qin2)

In this conversation, we cover:

- Starting [Rust-Lightning](https://github.com/rust-bitcoin/rust-lightning) (1:20)
- Language bindings challenges (4:09)
  - [FFI](https://en.m.wikipedia.org/wiki/Foreign_function_interface) (5:32)
- Interoperability of Lightning (7:10)
- [Zero-value invoices](https://suredbits.com/zero-amount-invoices/) (7:35)
- [Keysend/push payments/spontaneous payments](https://bitcoinops.org/en/topics/spontaneous-payments/) (8:20)
- What is the LDK stack? (9:29)
- [Anchor Outputs](https://bitcoinops.org/en/topics/anchor-outputs/) (10:41)
  - [Child pays for parent (CPFP)](https://bitcoinops.org/en/topics/cpfp/) (11:02)
- Who tracks the onchain state when using LND? (12:30)
- LDK tracks the channel commitment transaction, how is that done? (13:45)
  - [Compact block filters](https://bitcoinops.org/en/topics/compact-block-filters/)
- Contrasting multiple implementations working from a spec in Lighting vs. no spec with one dominant reference implementation in Bitcoin (14:58)
  - [The Lightning Spec](https://github.com/lightningnetwork/lightning-rfc/)
- What's the state of the Lightning Network? Have we moved beyond #reckless? (18:49)
  - Denial of Service (DoS) vulnerabilities
  - [Channel Jamming](https://bitcoinops.org/en/topics/channel-jamming-attacks/) (22:00)
- [Eltoo](https://bitcoinops.org/en/topics/eltoo/) and the punishment dynamic (22:45)
- Will the network trend to trusted relationships and lend itself to KYC? (24:50)
- [FATF updates its guidance on Virtual Asset Service Provider (VASP)](https://www.fatf-gafi.org/media/fatf/documents/recommendations/March%202021%20-%20VA%20Guidance%20update%20-%20Sixth%20draft%20-%20Public%20consultation.pdf) (26:50)
- Where LDK goes from here? (29:55)

Thanks to [Caralie](https://twitter.com/Caralie_C/) for the sound engineering.
