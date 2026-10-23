+++
date = '2022-11-16T00:00:00Z'
draft = false
title = "Sampling, Communication, and Prediction Co-Design for Synchronizing the Real-World Device and Digital Model in Metaverse"
tags = ["journal", "reinforcement-learning"]
+++

### Abstract
The metaverse has the potential to revolutionize the next generation of the Internet by supporting highly interactive services with the help of Mixed Reality (MR) technologies; still, to provide a satisfactory experience for users, the synchronization between the physical world and its digital models is crucial. This work proposes a sampling, communication and prediction co-design framework to minimize the communication load subject to a constraint on tracking the Mean Squared Error (MSE) between a real-world device and its digital model in the metaverse. To optimize the sampling rate and the prediction horizon, we exploit expert knowledge and develop a constrained Deep Reinforcement Learning (DRL) algorithm, named Knowledge-assisted Constrained Twin-Delayed Deep Deterministic (KC-TD3) policy gradient algorithm. We validate our framework on a prototype composed of a real-world robotic arm and its digital model. Compared with existing approaches: (1) When the tracking error constraint is stringent (MSE=0.002 degrees), our policy degenerates into the policy in the sampling-communication co-design framework. (2) When the tracking error constraint is mild (MSE=0.007 degrees), our policy degenerates into the policy in the prediction-communication co-design framework. (3) Our framework achieves a better trade-off between the average MSE and the average communication load compared with a communication system without sampling and prediction. For example, the average communication load can be reduced up to 87% when the track error constraint is 0.002 degrees. (4) Our policy outperforms the benchmark with the static sampling rate and prediction horizon optimized by exhaustive search, in terms of the tail probability of the tracking error. Furthermore, with the assistance of expert knowledge, the proposed algorithm KC-TD3 achieves better convergence time, stability, and final policy performance.

### Useful links
Paper: [https://doi.org/10.1109/jsac.2022.3221993](https://doi.org/10.1109/jsac.2022.3221993)

Preprint: [https://arxiv.org/abs/2208.04233](https://arxiv.org/abs/2208.04233)

### Bibtex

``` bibtex
@article{metaversecodesign2023,
  author={Meng, Zhen and She, Changyang and Zhao, Guodong and De Martini, Daniele},
  title={Sampling, Communication, and Prediction Co-Design for Synchronizing the Real-World Device and Digital Model in Metaverse},
  year={2023},
  journal={IEEE Journal on Selected Areas in Communications},
  volume={41},
  number={1},
  pages={288--300},
  doi={10.1109/jsac.2022.3221993},
  url={https://doi.org/10.1109/jsac.2022.3221993},
}
```
