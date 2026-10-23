+++
date = '2021-05-30T00:00:00Z'
draft = false
title = "Fool Me Once: Robust Selective Segmentation via Out-of-Distribution Detection with Contrastive Learning"
tags = ["conference", "uncertainty"]
+++

### Abstract
In this work, we train a network to simultaneously perform segmentation and pixel-wise Out-of-Distribution (OoD) detection, such that the segmentation of unknown regions of scenes can be rejected. This is made possible by leveraging an OoD dataset with a novel contrastive objective and data augmentation scheme. By combining data including unknown classes in the training data, a more robust feature representation can be learned with known classes represented distinctly from those unknown. When presented with unknown classes or conditions, many current approaches for segmentation frequently exhibit high confidence in their inaccurate segmentations and cannot be trusted in many operational environments. We validate our system on a real-world dataset of unusual driving scenes, and show that by selectively segmenting scenes based on what is predicted as OoD, we can increase the segmentation accuracy by an IoU of 0.2 with respect to alternative techniques.

### Useful links
Paper: [https://doi.org/10.1109/icra48506.2021.9561165](https://doi.org/10.1109/icra48506.2021.9561165)

Preprint: [https://arxiv.org/abs/2103.00869](https://arxiv.org/abs/2103.00869)

### Bibtex

``` bibtex
@inproceedings{foolmeonce2021,
  author={Williams, David S. W. and Gadd, Matthew and De Martini, Daniele and Newman, Paul},
  title={Fool Me Once: Robust Selective Segmentation via Out-of-Distribution Detection with Contrastive Learning},
  year={2021},
  booktitle={2021 IEEE International Conference on Robotics and Automation (ICRA)},
  pages={9536--9542},
  doi={10.1109/icra48506.2021.9561165},
  url={https://doi.org/10.1109/icra48506.2021.9561165},
}
```
