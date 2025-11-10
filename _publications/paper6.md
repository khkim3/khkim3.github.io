---
title: "Beyond RLHF and NLHF: Population-Proportional Alignment under an Axiomatic Framework"
collection: publications
category: conferences
excerpt: '**Kihyun Kim**, Jiawei Zhang, Asuman Ozdaglar, Pablo Parrilo'
date: 2025-06-01
venue: '(Under Review) arXiv preprint arXiv:2506.05619'
paperurl: 'https://arxiv.org/pdf/2506.05619'
citation: 
---

Conventional preference learning methods often prioritize opinions held more widely when aggregating preferences from multiple evaluators. This may result in policies that are biased in favor of some types of opinions or groups and  susceptible to strategic manipulation. To address this issue, we develop a novel preference learning framework capable of aligning aggregate opinions and policies proportionally with the true population distribution of evaluator preferences. Grounded in social choice theory, our approach infers the feasible set of evaluator population distributions directly from pairwise comparison data. Using these estimates, the algorithm constructs a policy that satisfies foundational axioms from social choice theory, namely monotonicity and Pareto efficiency, as well as our newly-introduced axioms of population-proportional alignment and population-bounded manipulability. Moreover, we propose a soft-max relaxation method that smoothly trade-offs population-proportional alignment with the selection of the Condorcet winner (which beats all other options in pairwise comparisons). Finally, we validate the effectiveness and scalability of our approach through experiments on both tabular recommendation tasks and large language model alignment.