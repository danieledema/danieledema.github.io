+++
date = '2019-05-20T12:00:00Z'
draft = false
title = 'Fast radar motion estimation with a learnt focus of attention using weak supervision'
tags = ["conference", "radar", "motion_estimation"]
+++

### Abstract

This paper is about fast motion estimation with scanning radar. We use weak supervision to train a focus of attention policy which actively down-samples the measurement stream before data association steps are undertaken. At training, we avoid laborious manual labelling by exploiting short-term sensor coherence from multiple poses in the presence of an external ego-motion estimator (for example, wheel odometry). At test time, we use the learnt policy to select a subset of the most informative radar measurements for motion estimation. We show that our approach can achieve comparable performance to using the full measurement stream while using only a fraction of the data, resulting in significant computational savings. We evaluate our approach on real radar data collected in challenging outdoor environments and demonstrate that our method can achieve accurate motion estimation while being computationally efficient.

### Useful links
Paper: [https://ieeexplore.ieee.org/document/8794014](https://ieeexplore.ieee.org/document/8794014)

### Bibtex
```bibtex
@inproceedings{Aldera2019FastRadar,
  author = {Aldera, Roberto and De Martini, Daniele and Gadd, Matthew and Newman, Paul},
  title = {Fast Radar Motion Estimation with a Learnt Focus of Attention using Weak Supervision},
  booktitle = {2019 International Conference on Robotics and Automation (ICRA)},
  year = {2019},
  pages = {1190--1196},
  publisher = {IEEE},
  address = {Montreal, QC, Canada},
  doi = {10.1109/ICRA.2019.8794014},
  month = {May}
}
```