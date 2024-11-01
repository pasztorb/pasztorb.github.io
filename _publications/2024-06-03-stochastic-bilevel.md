---
title: "Stochastic Bilevel Optimization with Lower-Level Contextual Markov Decision Processes"
collection: publications
permalink: /publication/2024-06-03-stochastic-bilevel

[//]: # (excerpt: 'This paper is about the number 1. The number 2 is left for future work.')
date: 2024-06-03
venue: 'ArXiv'
paperurl: 'https://arxiv.org/abs/2406.01575'
citation: Vinzenz Thoma, Barna Pasztor, Andreas Krause, Giorgia Ramponi, Yifan Hu. 2024. Stochastic Bilevel Optimization with Lower-Level Contextual Markov Decision Processes. ArXiv.
---

**Abstract**:
In various applications, the optimal policy in a strategic decision-making problem depends both on the environmental configuration and exogenous events.
For these settings, we introduce Bilevel Optimization with Contextual Markov Decision Processes (BO-CMDP),
a stochastic bilevel decision-making model, where the lower level consists of solving a contextual Markov Decision Process (CMDP).
BO-CMDP can be viewed as a Stackelberg Game where the leader and a random context beyond the leader’s control together decide the setup of (many) MDPs that (potentially multiple) followers best respond to.
This framework extends beyond traditional bilevel optimization and finds relevance in diverse fields such as model design for MDPs, tax design, reward shaping and dynamic mechanism design.
We propose a stochastic Hyper Policy Gradient Descent (HPGD) algorithm to solve BO-CMDP, and demonstrate its convergence.
Notably, HPGD only utilizes observations of the followers’ trajectories.
Therefore, it allows followers to use any training procedure and the leader to be agnostic of the specific algorithm used, which aligns with various real-world scenarios.
We further consider the setting when the leader can influence the training of followers and propose an accelerated algorithm.
We empirically demonstrate the performance of our algorithm.