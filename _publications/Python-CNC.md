---
title: "Python based 3-Axis CNC plotter:"
collection: publications
permalink: /publication/Python-CNC
excerpt: 'This paper is about open source architecture for CNC systems'
date: 2016-12-01
venue: 'IEEE'
paperurl: 'https://ieeexplore.ieee.org/document/7951672?anchor=footnotes'
citation: 'T. Shivakumar, M. S. Sravan and K. Selvajyothi, "Python based 3-Axis CNC plotter," 2016 IEEE International Conference on Power and Energy (PECon), Melaka, Malaysia, 2016, pp. 823-827, doi: 10.1109/PECON.2016.7951672.'
---
This paper presents an off-policy Gaussian Predictive Control (GPC) framework aimed at solving optimal control problems with a smaller computational footprint, thereby facilitating real-time applicability while ensuring critical safety considerations. The proposed controller imitates classical control methodologies by modeling the optimization process through a Gaussian process and employs Gaussian Process Regression to learn from the Model Predictive Control (MPC) algorithm.
Notably, the Gaussian Process setup does not incorporate a built-in model, enhancing its applicability to a broad range of control problems. We applied this framework experimentally to a differential drive mobile robot, tasking it with trajectory tracking and obstacle avoidance. Leveraging the off-policy aspect, the controller demonstrated adaptability to diverse trajectories and obstacle behaviors. Simulation experiments confirmed the effectiveness of the proposed GPC method,
emphasizing its ability to learn the dynamics of optimal control strategies. Consequently, our findings highlight the significant potential of off-policy Gaussian Predictive Control in achieving real-time optimal control for handling of robotic systems in safety-critical scenarios.

[Download paper here](https://arxiv.org/pdf/2403.10932.pdf)

Recommended citation: '@misc{tekumatla2024learningbased,
      title={Learning-Based Design of Off-Policy Gaussian Controllers: Integrating Model Predictive Control and Gaussian Process Regression}, 
      author={Shiva Kumar Tekumatla and Varun Gampa and Siavash Farzan},
      year={2024},
      eprint={2403.10932},
      archivePrefix={arXiv},
      primaryClass={cs.RO}
}'.

Architecture :

<img src='https://github.com/shivakumar-tekumatla/shivakumar-tekumatla.github.io/blob/master/files/GIFs/CNC.gif?raw=true' width =400  />