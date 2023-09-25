---
title: "Highway Reinforcement Learning"
collection: publications
permalink: /publication/highway_reinforcement_learning
excerpt: 'Traditional Dynamic Programming (DP) approaches suffer from slow backward credit-assignment (CA): only a one-step search is performed at each update. A popular solution for multi-step CA is to use multi-step Bellman operators. Unfortunately, in the control settings, existing methods typically suffer from the large variance of multi-step off-policy corrections or are biased, preventing convergence. To overcome these problems, we introduce a novel multi-step Bellman optimality equation with adaptive lookahead steps. We first derive a new multi-step Value Iteration (VI) method that converges to the optimal Value Function (VF) with an exponential contraction rate but linear computational complexity. Given some trial, our so-called Highway RL performs rapid CA, by picking a policy and a possible lookahead (up to the trial end) that maximize the near-term reward during lookahead plus a DP-based estimate of the cumulative reward for the remaining part of the trial. Highway RL does not require off-policy corrections. Under mild assumptions, it achieves better convergence rates than the traditional one-step Bellman Optimality Operator. We then derive Highway Q-Learning, a convergent multi-step off-policy variant of Q-learning. We show that our Highway algorithms significantly outperform DP approaches on toy tasks. Finally, we propose a deep function approximation variant called Highway DQN. We evaluate it on visual MinAtar Games, outperforming similar multi-step methods.'
date: 2022-09-29
venue: 'In Submission'
paperurl: 'https://openreview.net/pdf?id=NFcRC4aYSWf'
citation: '@misc{
wang2023highway,
title={Highway Reinforcement Learning},
author={Yuhui Wang and Haozhe Liu and Miroslav Strupl and Francesco Faccio and Qingyuan Wu and Xiaoyang Tan and J{\"u}rgen Schmidhuber},
year={2023},
url={https://openreview.net/forum?id=NFcRC4aYSWf}
}'
---
This paper is about reinforcement learning.

[Download paper here](https://openreview.net/pdf?id=NFcRC4aYSWf)

Recommended citation: '@misc{
wang2023highway,
title={Highway Reinforcement Learning},
author={Yuhui Wang and Haozhe Liu and Miroslav Strupl and Francesco Faccio and Qingyuan Wu and Xiaoyang Tan and J{\"u}rgen Schmidhuber},
year={2023},
url={https://openreview.net/forum?id=NFcRC4aYSWf}
}'