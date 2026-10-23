+++
date = '2025-10-19T00:00:00Z'
draft = false
title = "GraphSCENE: On-Demand Critical Scenario Generation for Autonomous Vehicles in Simulation"
tags = ["conference", "graph"]
+++

Finalist, IEEE-RAS Outstanding Women in Robotics & Automation (WiRA) Paper Awards at IROS 2025.

### Abstract
Testing and validating Autonomous Vehicle (AV) performance in safety-critical and diverse scenarios is crucial before real-world deployment. However, manually creating such scenarios in simulation remains a significant and time-consuming challenge. This work introduces a novel method that generates dynamic temporal scene graphs corresponding to diverse traffic scenarios, on-demand, tailored to user-defined preferences, such as AV actions, sets of dynamic agents, and criticality levels. A temporal Graph Neural Network (GNN) model learns to predict relationships between ego-vehicle, agents, and static structures, guided by real-world spatiotemporal interaction patterns and constrained by an ontology that restricts predictions to semantically valid links. Our model consistently outperforms the baselines in accurately generating links corresponding to the requested scenarios. We render the predicted scenarios in simulation to further demonstrate their effectiveness as testing environments for AV agents.

### Useful links
Paper: [https://doi.org/10.1109/iros60139.2025.11246040](https://doi.org/10.1109/iros60139.2025.11246040)

Preprint: [https://arxiv.org/abs/2410.13514](https://arxiv.org/abs/2410.13514)

### Bibtex

``` bibtex
@inproceedings{graphscene2025,
  author={Panagiotaki, Efimia and Pramatarov, Georgi and Kunze, Lars and De Martini, Daniele},
  title={GraphSCENE: On-Demand Critical Scenario Generation for Autonomous Vehicles in Simulation},
  year={2025},
  booktitle={2025 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)},
  pages={13801--13808},
  doi={10.1109/iros60139.2025.11246040},
  url={https://doi.org/10.1109/iros60139.2025.11246040},
}
```
