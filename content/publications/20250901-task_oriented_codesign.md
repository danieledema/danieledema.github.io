+++
date = '2025-09-01T00:00:00Z'
draft = false
title = "Task-Oriented Co-Design of Communication, Computing, and Control for Edge-Enabled Industrial Cyber-Physical Systems"
tags = ["journal"]
# Only the publication month is known; the first day is used for chronological sorting.
+++

### Abstract
This paper proposes a task-oriented co-design framework that integrates communication, computing, and control to address the key challenges of bandwidth limitations, noise interference, and latency in mission-critical industrial Cyber-Physical Systems (CPS). To improve communication efficiency and robustness, we design a task-oriented Joint Source-Channel Coding (JSCC) using Information Bottleneck (IB) to enhance data transmission efficiency by prioritizing task-specific information. To mitigate the perceived End-to-End (E2E) delays, we develop a Delay-Aware Trajectory-Guided Control Prediction (DTCP) strategy that integrates trajectory planning with control prediction, predicting commands based on E2E delay. Moreover, the DTCP is co-designed with task-oriented JSCC, focusing on transmitting task-specific information for timely and reliable autonomous driving. Experimental results in the CARLA simulator demonstrate that, under an E2E delay of 1 second (20 time slots), the proposed framework achieves a driving score of 48.12, which is 31.59 points higher than using Better Portable Graphics (BPG) while reducing bandwidth usage by 99.19%.

### Useful links
Paper: [https://doi.org/10.1109/jsac.2025.3574605](https://doi.org/10.1109/jsac.2025.3574605)

Preprint: [https://arxiv.org/abs/2503.08661](https://arxiv.org/abs/2503.08661)

### Bibtex

``` bibtex
@article{taskorientedcodesign2025,
  author={Diao, Yufeng and Zhang, Yichi and De Martini, Daniele and Zhao, Philip Guodong and Li, Emma Liying},
  title={Task-Oriented Co-Design of Communication, Computing, and Control for Edge-Enabled Industrial Cyber-Physical Systems},
  year={2025},
  journal={IEEE Journal on Selected Areas in Communications},
  volume={43},
  number={9},
  pages={3041--3055},
  doi={10.1109/jsac.2025.3574605},
  url={https://doi.org/10.1109/jsac.2025.3574605},
}
```
