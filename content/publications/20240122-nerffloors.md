+++
date = '2024-01-22T12:07:04Z'
draft = false
title = 'NeuralFloors: Conditional Street-Level Scene Generation From BEV Semantic Maps via Neural Fields'
tags = ["journal", "nerf", "generative"]
+++

### Abstract
Semantic Bird's Eye View (BEV) representations are a popular format, being easily interpretable and editable.
However, synthesising ground-view images from BEVs is a difficult task as the system would need to learn both the mapping from BEV to Front View (FV) structure as well as to synthesise highly photo-realistic imagery, thus having to simultaneously consider both the geometry and appearance of the scene.
We therefore present a factorised approach that tackles the problem in two stages: a first stage that learns a BEV to FV transformation in the semantic space through a Neural Field, and a second stage that leverages a Latent Diffusion Model (LDM) to synthesise images conditional on the output of the first stage.
Our experiments show that this approach produces RGB images with a high perceptual quality that are also well aligned with their corresponding FV ground-truth

### Useful links
Paper: [https://ieeexplore.ieee.org/abstract/document/10410883](https://ieeexplore.ieee.org/abstract/document/10410883)

### Bibtex 

``` bibtex
@INPROCEEDINGS{musat2024,
  author={Muşat, Valentina and De Martini, Daniele and Gadd, Matthew and Newman, Paul},
  journal={IEEE Robotics and Automation Letters}, 
  title={NeuralFloors: Conditional Street-Level Scene Generation From BEV Semantic Maps via Neural Fields}, 
  year={2024},
  volume={9},
  number={3},
  pages={2431-2438},
  keywords={Semantics;Three-dimensional displays;Solid modeling;Image segmentation;Cameras;Task analysis;Sensors;Deep learning for visual perception;computer vision for transportation;neural rendering;cross-view transformation;data-driven simulation},
  doi={10.1109/LRA.2024.3356793}}
```
