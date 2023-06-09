---
title: "Efficient Model-Based Multi-Agent Mean-Field Reinforcement Learning"
collection: talks
type: "Talk"
permalink: /talks/2023-06-06-mf_mfg_webinar_talk
venue: "Machine Learning and Mean-Field Games Seminar"
date: 2023-06-06
location: "Online"
---

* Recording: [YouTube](https://www.youtube.com/watch?v=2O2KU3A7BEY)
* Slides: [PDF](https://drive.google.com/file/d/1InxyRN178srjYqGiCUT3pH3EPsbzB8Zi/view?usp=sharing)


### Abstract
Learning in multi-agent systems is highly challenging due to several factors including the non-stationarity introduced
by agents' interactions and the combinatorial nature of their state and action spaces. In particular, we consider the
Mean-Field Control (MFC) problem which assumes an asymptotically infinite population of identical agents that aim to
collaboratively maximize the collective reward. In many cases, solutions of an MFC problem are good approximations for
large systems, hence, efficient learning for MFC is valuable for the analogous discrete agent setting with many agents.
Specifically, we focus on the case of unknown system dynamics where the goal is to simultaneously optimize for the
rewards and learn from experience. We propose an efficient model-based reinforcement learning algorithm, M3-UCRL, that
runs in episodes, balances between exploration and exploitation during policy learning, and provably solves this problem.
Our main theoretical contributions are the first general regret bounds for model-based reinforcement learning for MFC,
obtained via a novel mean-field type analysis. To learn the system’s dynamics, M3-UCRL can be instantiated with various
statistical models, e.g., neural networks or Gaussian Processes. Moreover, we provide a practical parametrization of the
core optimization problem that facilitates gradient-based optimization techniques when combined with differentiable
dynamics approximation methods such as neural networks.