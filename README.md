# Blockchain Theory

Coursework for **Blockchain Theory** at the University of Tehran, Faculty of Electrical and Computer Engineering (Spring 2025, Dr. Shariatpanahi & Dr. Akhaee).

## Research project – RapidChain

[research-project-rapidchain/](research-project-rapidchain/) is an in-depth study of *RapidChain: Scaling Blockchain via Full Sharding* (Zamani, Movahedi & Raykova, CCS 2018), with a written report and a presentation. The report:

- places RapidChain against Nakamoto, committee-based (ByzCoin, Solida) and earlier sharding (Elastico, OmniLedger) consensus
- walks through its three phases: **bootstrapping** without a trusted setup (sampler graphs, multi-level committee election), intra-committee **consensus** with 1/3 fault tolerance, and **reconfiguration** to resist adaptive adversaries
- analyses the throughput, latency and bootstrapping costs reported for a 4,000-node network

## Homework

| # | Topic | Solution |
|---|-------|----------|
| 1 | Cryptography: hash functions for proof-of-work, Merkle trees, Bitcoin addresses, elliptic-curve cryptography, three-party Diffie–Hellman, RSA with a shared modulus | [hw1-cryptography.pdf](homework/hw1-cryptography.pdf) |
| 2 | Bitcoin mechanics: UTXOs, Bitcoin Script, mining, lightweight clients, soft vs. hard forks, orphaned blocks, block-time analysis | [hw2-bitcoin-mechanics.pdf](homework/hw2-bitcoin-mechanics.pdf) |
| 3 | Peer-to-peer networks: randomised push gossip in the Bitcoin network | [hw3-p2p-networks.pdf](homework/hw3-p2p-networks.pdf) |
| 4 | Distributed consensus: Byzantine fault tolerance in PBFT, Raft | [hw4-consensus-pbft-raft.pdf](homework/hw4-consensus-pbft-raft.pdf) |
| 5 | Proof-of-stake security: apparent-stake attacks | [hw5-proof-of-stake-attacks.pdf](homework/hw5-proof-of-stake-attacks.pdf) |

Homework 2 is answered in English; the others are in Persian.
