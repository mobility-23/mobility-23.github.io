---
title: "Real-time optimal trajectory planning for autonomous driving with collision avoidance using convex optimization"
collection: publications
permalink: /publication/Guo-AI-23
date: 2023-08-01
venue: 'Automotive Innovation'
paperurl: 'https://link.springer.com/article/10.1007/s42154-023-00222-7'
pubtype: 'journal'
authors: 'Guoqiang Li, Xudong Zhang, Hongliang Guo, Basilio Lenzo, Ningyuan Guo'
excerpt_separator: ""
---

An online trajectory planning method for collision avoidance is proposed to improve vehicle driving safety and comfort simultaneously. The collision-free trajectory for autonomous driving is formulated as a nonlinear optimization problem. A novel approximate convex optimization approach is developed for the online optimal trajectory in both longitudinal and lateral directions. First, a dual variable is used to model the non-convex collision-free constraint for driving safety and is calculated by solving a dual problem of the relative distance between vehicles. Second, the trajectory is further optimized in a model predictive control framework considering the safety. It realizes continuous-time and dynamic feasible motion with collision avoidance. The geometry of object vehicles is described by polygons instead of circles or ellipses in traditional methods. In order to avoid aggressive maneuver in the longitudinal and lateral directions for driving comfort, rates of the acceleration and the steering angle are restricted. The final formulated optimization problem is convex, which can be solved by using quadratic programming solvers and is computationally efficient for online application. Simulation results show that this approach can obtain similar driving performance compared to a state-of-the-art nonlinear optimization method. Furthermore, various driving scenarios are tested to evaluate the robustness and the ability for handling complex driving tasks.
