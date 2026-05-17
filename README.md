# csac-arm

This is the materials and supplements of "**Energy-Aware Reinforcement Learning for Robotic Manipulation in Intelligent Infrastructure Operation and Maintenance**".

**ABSTRACT**: With the growth of intelligent civil infrastructure and smart cities, operation and maintenance (O&M) increasingly requires safe, efficient, and energy-conscious robotic manipulation of articulated components, including access doors, service drawers, and pipeline valves. However, existing robotic approaches either focus primarily on grasping or target object-specific articulated manipulation, and they rarely incorporate explicit actuation energy into multi-objective optimisation, which limits their scalability and suitability for long-term deployment in real O&M settings. Therefore, this paper proposes an articulation-agnostic and energy-aware reinforcement learning framework for robotic manipulation in intelligent infrastructure O&M. The method combines part-guided 3D perception, weighted point sampling, and PointNet-based encoding to obtain a compact geometric representation that generalises across heterogeneous articulated objects. Manipulation is formulated as a Constrained Markov Decision Process (CMDP), in which actuation energy is explicitly modelled and regulated via a Lagrangian-based constrained Soft Actor-Critic scheme. The policy is trained end-to-end under this CMDP formulation, enabling effective articulated-object operation while satisfying a long-horizon energy budget. Experiments on representative O&M tasks demonstrate 16%-30% reductions in energy consumption, 16%-32% fewer steps to success, and consistently high success rates, indicating a scalable and sustainable solution for infrastructure O&M manipulation.

This work has been published on [Computer-Aided Civil and Infrastructure Engineering](https://www.sciencedirect.com/journal/computer-aided-civil-and-infrastructure-engineering),  to cite this work:

```bib
@article{TAO2026100015,
title = {Energy-aware reinforcement learning for robotic manipulation of articulated components in infrastructure operation and maintenance},
journal = {Computer-Aided Civil and Infrastructure Engineering},
pages = {100015},
year = {2026},
issn = {1093-9687},
doi = {https://doi.org/10.1016/j.cacaie.2026.100015},
url = {https://www.sciencedirect.com/science/article/pii/S1093968726025934},
author = {Xiaowen Tao and Yinuo Wang and Haitao Ding and Yuanyang Qi and Ziyu Song},
}
```

**Click to view the video:**

<a href="https://youtu.be/j1LtAxwpzLA" target="_blank">
<img src="https://github.com/user-attachments/assets/0e63a565-b13d-40c4-a44b-894c3b96f106" 
     alt="Watch the video"
     width="400"
     style="border: 3px solid #333; border-radius: 8px;"
/>
</a>
