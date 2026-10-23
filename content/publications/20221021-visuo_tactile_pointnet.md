+++
date = '2022-10-21T00:00:00Z'
draft = false
title = "Visuo-Tactile Recognition of Partial Point Clouds Using PointNet and Curriculum Learning: Enabling Tactile Perception from Visual Data"
tags = ["journal"]
+++

### Abstract
This paper is about recognising hand-held objects from incomplete tactile observations with a classifier trained only on visual representations. Our method is based on the Deep Learning (DL) architecture PointNet and a Curriculum Learning (CL) technique for fostering the learning of descriptors robust to partial representations of objects. The learning procedure gradually decomposes the visual point clouds to synthesise sparser and sparser input data for the model. In this manner, we were able to use one-shot learning, using the decomposed visual point clouds as augmentations, and reduce the data-collection requirement for training. The approach allows for a gradual improvement of prediction accuracy as more tactile data become available. We evaluated the effectiveness of the curriculum strategy on our generated visual and tactile datasets, experimentally showing that the proposed method improved the recognition accuracy by up to 23% on partial tactile data and boosted accuracy on full tactile data from 93% to 100%. The curriculumtrained network recognised objects with an accuracy of 80% using only 20% of the tactile data representing the objects, increasing to 100% accuracy on clouds containing at least 60% of the points.

### Useful links
Paper: [https://doi.org/10.1109/mra.2022.3212316](https://doi.org/10.1109/mra.2022.3212316)

Publication record: [https://ora.ox.ac.uk/objects/uuid:1d39fe8c-d699-4be7-b609-498ab7c577fa](https://ora.ox.ac.uk/objects/uuid:1d39fe8c-d699-4be7-b609-498ab7c577fa)

### Bibtex

``` bibtex
@article{visuotactilepointnet2023,
  author={Parsons, Christopher and Albini, Alessandro and De Martini, Daniele and Maiolino, Perla},
  title={Visuo-Tactile Recognition of Partial Point Clouds Using PointNet and Curriculum Learning: Enabling Tactile Perception from Visual Data},
  year={2023},
  journal={IEEE Robotics \& Automation Magazine},
  volume={30},
  number={3},
  pages={69--78},
  doi={10.1109/mra.2022.3212316},
  url={https://doi.org/10.1109/mra.2022.3212316},
}
```
