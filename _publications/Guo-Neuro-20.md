---
title: "Integrated adaptive dynamic programming for data-driven optimal controller design"
collection: publications
permalink: /publication/Guo-Neuro-20
date: 2020-08-25
venue: 'Neurocomputing'
paperurl: 'https://www.sciencedirect.com/science/article/abs/pii/S0925231220306809'
pubtype: 'journal'
authors: 'Guoqiang Li, Daniel Goerges, Chaoxu Mu'
excerpt_separator: ""
---
In this paper a novel integrated adaptive dynamic programming method with an advantage function is developed to solve model-free optimal control problems and improve the control performance. The advantage function is utilized to evaluate the cost resulting from the action (control variables) which does not follow the optimal control policy. The Q function in Q-learning can thus be built from a value function and the advantage function. The control policy is then improved through minimizing the Q function. To employ the proposed algorithm, an integrated multi-layer neural network (INN) is designed for the value function and the control variables. Only one single neural network requires adaption. This avoids the iterative learning of two separate networks in the heuristic dynamic programming-based methods. Simulation for linear and non-linear optimal control problems is studied. Comparing to the optimal solutions resulting from the linear quadratic regulator and dynamic programming (DP), the proposed INN design can lead to closer control performance than the ones with action dependent heuristic dynamic programming (ADHDP). Furthermore INN is applied to optimize the energy management strategy of hybrid electric vehicles for fuel economy. The fuel consumption based on INN is lower than the one from ADHDP and much closer to the optimal results by DP. The result indicates the near fuel-optimality and an effective practical application.
