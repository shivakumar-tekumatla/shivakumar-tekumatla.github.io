---
title: "D* and Informed RRT*"
excerpt: "Motion planning for mobile robots in dynamic environment"
collection: portfolio
---
Traditional discrete planning based algorithms fail to perform in the dynamic environments.For eample, A* path can be computed assuming each state of the change in environment as static , and then recompute every time the environment or obstacles are changed. However, this is a very slow process ,and by the time a feasible path is found by A* , the dynamics of the environment may change. This is where D* algorithm helps. D* is known as dynamic A * , which uses local re-planning to reconstruct the damaged path. In this paper, I discuss the implementation of D* algorithm. In sampling based methods, RRT and RRT* are well known and can be used to find the feasible path in static environments. RRT* simply uses rewiring method to optimized the path computed by RRT. In RRT* , while rewiring , the samples are randomly formed again in an entire work space. However, in informed RRT*, the samples are formed in a locally formed ellipse with start and goal positions as foci. Informed RRT* is faster compared in RRT* and can result in better and optimized paths. In this paper, I discuss the implementation of informed RRT*, and compare the results with
RRT star 

Report for this project can be [downloaded here](https://github.com/shivakumar-tekumatla/shivakumar-tekumatla.github.io/blob/master/files/D*.pdf). 

