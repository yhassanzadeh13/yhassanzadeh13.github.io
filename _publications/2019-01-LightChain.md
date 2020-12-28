---
title: "LightChain: A DHT-based Blockchain for Resource Constrained Environments"
collection: publications
permalink: /publication/2019-01-LightChain
excerpt: ''
date: 2019-3-31
venue: 'Arxiv'
paperurl: 'https://arxiv.org/pdf/1904.00375.pdf'
---
As an append-only distributed database, blockchain is utilized in a vast variety of applications including the cryptocurrency and Internet-of-Things (IoT). The existing blockchain solutions have downsides in communication and storage efficiency, convergence to centralization, and consistency problems. In this paper, we propose LightChain, which is the first blockchain architecture that operates over a Distributed Hash Table (DHT) of participating peers. LightChain is a permissionless blockchain that provides addressable blocks and transactions within the network, which makes them efficiently accessible by all the peers. Each block and transaction is replicated within the DHT of peers and is retrieved in an on-demand manner. Hence, peers in LightChain are not required to retrieve or keep the entire blockchain. LightChain is fair as all of the participating peers have a uniform chance of being involved in the consensus regardless of their influence such as hashing power or stake. LightChain provides a deterministic fork-resolving strategy as well as a blacklisting mechanism, and it is secure against colluding adversarial peers attacking the availability and integrity of the system. We provide mathematical analysis and experimental results on scenarios involving 10K nodes to demonstrate the security and fairness of LightChain.

[Download paper here](https://arxiv.org/pdf/1904.00375.pdf)

Recommended citation: Hassanzadeh-Nazarabadi, Yahya, Alptekin Küpçü, and Öznur Özkasap. "LightChain: A DHT-based blockchain for resource constrained environments." arXiv preprint arXiv:1904.00375 (2019)..
