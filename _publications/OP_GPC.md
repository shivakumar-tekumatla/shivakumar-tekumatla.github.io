---
title: "Learning-Based Design of Off-Policy Gaussian Controllers: Integrating Model Predictive Control and Gaussian Process Regression"
collection: publications
permalink: /publication/OP_GPC
excerpt: 'This paper is about off policy gaussian predictive controller'
date: 
venue: 'American Control Conference 2024'
paperurl: ''
citation: 'Tekumatla SK, Gampa V, Farzan S. Learning-Based Design of Off-Policy Gaussian Controllers: Integrating Model Predictive Control and Gaussian Process Regression. arXiv preprint arXiv:2403.10932. 2024 Mar 16.'
---
This paper presents an off-policy Gaussian Predictive Control (GPC) framework aimed at solving optimal control problems with a smaller computational footprint, thereby facilitating real-time applicability while ensuring critical safety considerations. The proposed controller imitates classical control methodologies by modeling the optimization process through a Gaussian process and employs Gaussian Process Regression to learn from the Model Predictive Control (MPC) algorithm. Notably, the Gaussian Process setup does not incorporate a built-in model, enhancing its applicability to a broad range of control problems. We applied this framework experimentally to a differential drive mobile robot, tasking it with trajectory tracking and obstacle avoidance. Leveraging the off-policy aspect, the controller demonstrated adaptability to diverse trajectories and obstacle behaviors. Simulation experiments confirmed the effectiveness of the proposed GPC method, emphasizing its ability to learn the dynamics of optimal control strategies. Consequently, our findings highlight the significant potential of off-policy Gaussian Predictive Control in achieving real-time optimal control for handling of robotic systems in safety-critical scenarios.

Link to the paper - https://arxiv.org/abs/2403.10932 

Recommended Citation : '@misc{tekumatla2024learningbased,
      title={Learning-Based Design of Off-Policy Gaussian Controllers: Integrating Model Predictive Control and Gaussian Process Regression}, 
      author={Shiva Kumar Tekumatla and Varun Gampa and Siavash Farzan},
      year={2024},
      eprint={2403.10932},
      archivePrefix={arXiv},
      primaryClass={cs.RO}
}'