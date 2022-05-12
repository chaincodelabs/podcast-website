---
title: "Martin Zumsande and Address Relay"
tags:
  - p2p
  - addrRelay
  - addrMan
---

[Martin Zumsande](https://twitter.com/Lightlike1) joins us to tell us about the address spam in the summer of 2021 and his interests in AddrRelay and Bitcoin Core development.

<iframe src="FIXME" height="102px" width="400px" frameborder="0" scrolling="no"></iframe>

[anchor.fm](FIXME)

We discuss with Martin:

- Martin's background (1:38)
- Getting interested in Bitcoin (2:45)
- How to approach P2P (3:55)
- The network is changing (7:30)
- What's the purpose of the Address Manager (AddrMan)? (9:33)
    - Peering differences to LN nodes (11:00)
    - [Ethan Heilman's talk on Network Partitioning Attacks](https://btctranscripts.com/chaincode-labs/chaincode-residency/2019-06-12-ethan-heilman-network-partitioning-attacks/) (12:10)
- AddrRelay and the role of node addresses (12:55)
    - Getting connected to the network (13:37)
    - Self-announcements (14:25)
- Address spam in summer 2021 and peer distribution (15:05)
    - Correction: The peer would not get addresses-divided-by-peers addresses, but 2×addresses-divided-by-peers addresses as the addresses get forwarded to two peers each. (18:00)
    - [Estimating the Node Degree of Public Peers and Detecting Sybil Peers Based on Address Messages in the Bitcoin P2P Network](https://arxiv.org/abs/2108.00815) by Matthias Grundmann (19:30)
- Simulating the network (20:15)
- Requesting addresses from peers (21:45)
- Walking through first connection of a node (25:25)
    - [Coinscope paper](https://www.cs.umd.edu/projects/coinscope/coinscope.pdf) (27:10)
- Being a Bitcoin Core contributor (27:50)

Thanks to [Emily](#FIXME) for the sound engineering.
