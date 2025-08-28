---
title: "Population-Proportional Preference Learning from Human Feedback: An Axiomatic Approach"
collection: publications
category: conferences
permalink: /publication/paper6
excerpt: 'Kihyun Kim, Jiawei Zhang, Asuman Ozdaglar, Pablo Parrilo'
date: 2025-06-01
venue: '(Under Review) arXiv preprint arXiv:2506.05619'
paperurl: 'https://arxiv.org/pdf/2506.05619'
citation: 
---

Conventional preference learning methods often prioritize opinions held more widely when aggregating preferences from multiple evaluators. This may result in policies that are biased in favor of some types of opinions or groups. The objective of this paper is to develop a novel preference learning framework capable of aligning aggregate opinions and policies proportionally with the true population distribution of evaluator preferences. Our approach infers the feasible set of evaluator population distributions directly from pairwise comparison data. Using these estimates, the algorithm constructs a policy that satisfies foundational axioms from social choice theory, namely monotonicity and Pareto efficiency, as well as our newly-introduced axioms of population-proportional representation and population-bounded robustness. We propose a soft-max relaxation method that smoothly trade-offs population-proportional representation with the selection of the Condorcet winner (which beats all other options in pairwise comparisons). Finally, we validate the effectiveness and scalability of our approach through experiments on both tabular recommendation tasks and large-scale language model alignment.