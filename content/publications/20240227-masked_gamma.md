+++
date = '2024-02-27T12:07:04Z'
draft = false
title = 'Masked γ-SSL: Learning Uncertainty Estimation via Masked Image Modeling'
tags = ["conference", "Uncertainty"]
+++

### Abstract
This work proposes a semantic segmentation network that produces high-quality uncertainty estimates in a single forward pass.
We exploit general representations from foundation models and unlabelled datasets through a Masked Image Modeling (MIM) approach, which is robust to augmentation hyper-parameters and simpler than previous techniques.
For neural networks used in safety-critical applications, bias in the training data can lead to errors; therefore it is crucial to understand a network’s limitations at run time and act accordingly.
To this end, we test our proposed method on a number of test domains including the SAX Segmentation benchmark, which includes labelled test data from dense urban, rural and off-road driving domains.
The proposed method consistently outperforms uncertainty estimation and Out-of-Distribution (OoD) techniques on this difficult benchmark

### Useful links
Paper: [https://ieeexplore.ieee.org/document/10610398](https://ieeexplore.ieee.org/document/10610398)

### Bibtex 

``` bibtex
@INPROCEEDINGS{williams2024,
  author={Williams, David S. W. and Gadd, Matthew and Newman, Paul and De Martini, Daniele},
  booktitle={2024 IEEE International Conference on Robotics and Automation (ICRA)}, 
  title={Masked γ-SSL: Learning Uncertainty Estimation via Masked Image Modeling}, 
  year={2024},
  volume={},
  number={},
  pages={16192-16198},
  keywords={Training;Uncertainty;Semantic segmentation;Neural networks;Estimation;Training data;Benchmark testing;Segmentation;Scene Understanding;Introspection;Performance Assessment;Deep Learning;Autonomous Vehicles},
  doi={10.1109/ICRA57147.2024.10610398}}
```
