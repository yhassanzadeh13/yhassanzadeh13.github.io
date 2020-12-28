---
title: "Interlaced: Fully decentralized churn stabilization for Skip Graph-based DHTs"
collection: publications
permalink: /publication/2020-05-Interlaced.md
excerpt: ''
date: 2020-11-05
venue: 'Journal of Parallel and Distributed Computing, Elsevier'
paperurl: 'https://arxiv.org/pdf/1903.07289'
citation: ''
---
As a distributed hash table (DHT) routing overlay, Skip Graph is used in a variety of peer-to-peer (P2P) systems including cloud storage, social networks, and search engines. The overlay connectivity of P2P systems is negatively affected by the arrivals and departures of nodes to and from the system that is known as churn. Preserving connectivity of the overlay network (ie, the reachability of every pair of nodes) under churn is a performance challenge in every P2P system including the Skip Graph-based ones. The existing decentralized churn stabilization solutions that are applicable on Skip Graphs have intensive communication complexities, which leave them unable to provide a strong overlay connectivity, especially under high rates of churn.
In this paper, we propose Interlaced, a fully decentralized churn stabilization mechanism for Skip Graphs that provides drastically stronger overlay connectivity without changing the asymptotic complexity of the Skip Graph in terms of storage, computation, and communication. We also propose the Sliding Window De Bruijn Graph (SW-DBG) as a tool to predict the availability of nodes with high accuracy. Our simulation results show that in comparison to the best existing DHT-based solutions, Interlaced improves the overlay connectivity of Skip Graph under churn with the gain of about 1.81 times. A Skip Graph that benefits from Interlaced and SW-DBG is about 2.47 times faster on average in routing the queries under churn compared to the best existing solutions. We also present an adaptive extension of Interlaced to be applied on other DHTs, for example Kademlia.

[Download paper here (Arxiv)](https://arxiv.org/pdf/1903.07289.pdf)
[Download paper here (Elsevier)](https://www.sciencedirect.com/science/article/pii/S0743731520303919?dgcid=author)

Recommended citation: Hassanzadeh-Nazarabadi, Yahya, Alptekin Küpçü, and Öznur Özkasap. "Interlaced: Fully decentralized churn stabilization for skip graph-based dhts." Journal of Parallel and Distributed Computing, Volume 149, Pages 13-28, ISSN 0743-7315, Elesiver, 2020, https://doi.org/10.1016/j.jpdc.2020.10.008..
