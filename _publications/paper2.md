---
title: "Optimizing large‑scale fleet management on a road network using multi‑agent deep reinforcement learning with graph neural network"
collection: publications
category: conferences
permalink: /publication/paper2
excerpt: 'Juhyeon Kim, Kihyun Kim'
date: 2021-01-01
venue: 'IEEE International Intelligent Transportation Systems Conference (ITSC)'
slidesurl:
paperurl: 'https://arxiv.org/pdf/2011.06175'
citation: 
---

We propose a novel approach to optimize fleet management by combining multi-agent reinforcement learning with graph neural network. To provide ride-hailing service, one needs to optimize dynamic resources and demands over spatial domain. While the spatial structure was previously approximated with a regular grid, our approach represents the road network with a graph, which better reflects the underlying geometric structure. Dynamic resource allocation is formulated as multi-agent reinforcement learning, whose actionvalue function (Q function) is approximated with graph neural networks. We use stochastic policy update rule over the graph with deep Q-networks (DQN), and achieve superior results over the greedy policy update. We design a realistic simulator that emulates the empirical taxi call data, and confirm the effectiveness of the proposed model under various conditions.