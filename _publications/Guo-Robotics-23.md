---
title: "Online trajectory optimization for safe autonomous overtaking with active obstacle avoidance"
collection: publications
permalink: /publication/Guo-Robotics-23
date: 2023-11-01
venue: 'Robotics and Autonomous Systems'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0921889023001677'
pubtype: 'journal'
authors: 'Guoqiang Li, Hongliang Guo, Zhenpo Wang, Meng Wang'
excerpt_separator: ""
---

Autonomous driving with active obstacle avoidance in dynamic urban environment has attracted significant attention to improve road safety and traffic efficiency. In this paper, an online optimization-based trajectory planning method for autonomous overtaking is developed to prevent collision and realize safe efficient driving. Unlike traditional methods which solve the overtaking problem with segmented reference path in multi-stages with integer variables, this paper proposes a novel dual-variable trajectory planning framework to get the optimal trajectory for active collision avoidance. First, the nonlinear non-differentiable collision-free constraint between vehicles is reformulated using dual problem optimization. Then, the optimal trajectory for longitudinal and lateral movement is obtained jointly in a receding horizon optimization framework based on the optimized dual variable considering the safety and dynamic performance. The key novelty lies in the reformulation of the nonlinear optimal trajectory planning problem and the formulated whole optimization framework can be solved using efficient open-source solvers for online computation. Simulation studies in different dynamic cases are provided to show the efficiency and robustness for safe driving. The method reaches safe overtaking performance with much less calculation time. Real-world experiment with a static obstacle demonstrates its capability for the safe efficient trajectory planning and online implementation in autonomous driving.
