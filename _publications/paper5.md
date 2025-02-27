---
title: "A Unified Linear Programming Framework for Offline Reward Learning from Human Demonstrations and Feedback"
collection: publications
category: conferences
permalink: /publication/paper5
excerpt: 'Kihyun Kim, Jiawei Zhang, Asuman Ozdaglar, Pablo Parrilo'
date: 2024-01-02
venue: 'International Conference on Machine Learning (ICML)'
paperurl: 'https://arxiv.org/pdf/2405.12421'
citation: 
---

Inverse Reinforcement Learning (IRL) and Reinforcement Learning from Human Feedback (RLHF) are pivotal methodologies in reward learning, which involve inferring and shaping the underlying reward function of sequential decision-making problems based on observed human demonstrations and feedback. Most prior work in reward learning has relied on prior knowledge or assumptions about decision or preference models, potentially leading to robustness issues. In response, this paper introduces a novel linear programming (LP) framework tailored for offline reward learning. Utilizing pre-collected trajectories without online exploration, this framework estimates a feasible reward set from the primaldual optimality conditions of a suitably designed LP, and offers an optimality guarantee with provable sample efficiency. Our LP framework also enables aligning the reward functions with human feedback, such as pairwise trajectory comparison data, while maintaining computational tractability and sample efficiency. We demonstrate that our framework potentially achieves better performance compared to the conventional maximum likelihood estimation (MLE) approach through analytical examples and numerical experiments.