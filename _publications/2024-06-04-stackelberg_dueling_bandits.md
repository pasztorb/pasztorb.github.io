---
title: "Bandits with Preference Feedback: A Stackelberg Game Perspective"
collection: publications
permalink: /publication/2024-06-04-stackelberg_dueling_bandits

[//]: # (excerpt: 'This paper is about the number 1. The number 2 is left for future work.')
date: 2024-06-03
venue: 'FoRLaC ICML Workshop (2024)'
paperurl: 'https://openreview.net/forum?id=FUKfuDzo3o&referrer=%5Bthe%20profile%20of%20Barna%20Pásztor%5D(%2Fprofile%3Fid%3D~Barna_Pásztor1)'
---
[Download paper here](https://openreview.net/pdf?id=FUKfuDzo3o)

**Abstract**:
Bandits with preference feedback present a powerful tool for optimizing unknown target functions when only pairwise comparisons are allowed instead of direct value queries.
This model allows for incorporating human feedback into online inference and optimization and has been employed in systems for tuning large language models.
The problem is well understood in simplified settings with linear target functions or over finite small domains that limit practical interest.
Taking the next step, we consider infinite domains and nonlinear (kernelized) rewards.
In this setting, selecting a pair of actions is quite challenging and requires balancing exploration and exploitation at two levels: within the pair, and along the iterations of the algorithm.
We propose MaxMinLCB, which emulates this trade-off as a zero-sum Stackelberg game and chooses action pairs that are informative and yield favorable rewards.
MaxMinLCB consistently outperforms existing algorithms and satisfies an anytime-valid rate-optimal regret guarantee.
This is due to our novel preference-based confidence sequences for kernelized logistic estimators.