+++
date = '2021-12-06T00:00:00Z'
draft = false
title = "Contrastive Learning for Unsupervised Radar Place Recognition"
tags = ["conference", "radar", "localisation"]
+++

### Abstract
We learn, in an unsupervised way, an embedding from sequences of radar images that is suitable for solving the place recognition problem with complex radar data. Our method is based on invariant instance feature learning but is tailored for the task of re-localisation by exploiting for data augmentation the temporal successivity of data as collected by a mobile platform moving through the scene smoothly. We experiment across two prominent urban radar datasets totalling over 400 km of driving and show that we achieve a new radar place recognition state-of-the-art. Specifically, the proposed system proves correct for 98.38% of the queries that it is presented with over a challenging re-localisation sequence, using only the single nearest neighbour in the learned metric space. We also find that our learned model shows better understanding of out-of-lane loop closures at arbitrary orientation than non-learned radar scan descriptors.

### Useful links
Paper: [https://doi.org/10.1109/icar53236.2021.9659335](https://doi.org/10.1109/icar53236.2021.9659335)

Preprint: [https://arxiv.org/abs/2110.02744](https://arxiv.org/abs/2110.02744)

### Bibtex

``` bibtex
@inproceedings{contrastiveradarplacerecognition2021,
  author={Gadd, Matthew and De Martini, Daniele and Newman, Paul},
  title={Contrastive Learning for Unsupervised Radar Place Recognition},
  year={2021},
  booktitle={2021 20th International Conference on Advanced Robotics (ICAR)},
  doi={10.1109/icar53236.2021.9659335},
  url={https://doi.org/10.1109/icar53236.2021.9659335},
}
```
