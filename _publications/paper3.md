---
title: "Minimax control of ambiguous linear stochastic systems using the Wasserstein metric"
collection: publications
category: manuscripts
permalink: /publication/paper3
excerpt: 'Kihyun Kim, Insoon Yang'
date: 2020-01-02
venue: 'IEEE Conference on Decision and Control (CDC)'
slidesurl:
paperurl: 'https://arxiv.org/pdf/2003.13258'
citation:
---

In this paper, we propose a minimax linearquadratic control method to address the issue of inaccurate distribution information in practical stochastic systems. To construct a control policy that is robust against errors in an empirical distribution of uncertainty, our method is to adopt an adversary, which selects the worst-case distribution. To systematically adjust the conservativeness of our method, the opponent receives a penalty proportional to the amount, measured with the Wasserstein metric, of deviation from the empirical distribution. In the finite-horizon case, using a Riccati equation, we derive a closed-form expression of the unique optimal policy and the opponent's policy that generates the worst-case distribution. This result is then extended to the infinite-horizon setting by identifying conditions under which the Riccati recursion converges to the unique positive semidefinite solution to an associated algebraic Riccati equation (ARE). The resulting optimal policy is shown to stabilize the expected value of the system state under the worst-case distribution. We also discuss that our method can be interpreted as a distributional generalization of the H-infinity method.