+++
date = '2024-10-14T12:07:04Z'
draft = false
title = 'NeuralFloors: Conditional street-level scene generation from BEV semantic maps via Neural Fields"
tags = ["journal", "nerf", "geenrativeai"]
+++

### Abstract
Learning autonomous driving capabilities requires diverse and realistic training data.
This has led to exploring generative techniques as an alternative to real-world data collection.
In this paper we propose a method for synthesising photo-realistic urban driving scenes, along with semantic, instance and depth ground-truth.
Our model relies on Bird’s Eye View (BEV) representations due to their compositionality and scene content control capabilities, reducing the need for traditional simulators.
We employ a two-stage process: first, a 3D scene representation is extracted from BEV semantic, instance and style maps using a neural field.
After rendering the semantic, instance, depth and style maps from a ground-view perspective, a second stage based on a diffusion model is used to generate the photo-realistic scene.
We extend our prior work - NeuralFloors, to include multiple-view outputs, style manipulation for finer control at the object level through instance-wise style maps and cross-frame consistency via auto-regressive training.
The proposed system is evaluated extensively on the KITTI-360 dataset, showing improved realism and semantic alignment for generated images

### Useful links
Paper: [https://ieeexplore.ieee.org/abstract/document/10802002](https://ieeexplore.ieee.org/abstract/document/10802002)

### Bibtex 

``` bibtex
@INPROCEEDINGS{10802002,
  author={Muşat, Valentina and De Martini, Daniele and Gadd, Matthew and Newman, Paul},
  booktitle={2024 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)}, 
  title={NeuralFloors++: Consistent Street-Level Scene Generation From BEV Semantic Maps}, 
  year={2024},
  volume={},
  number={},
  pages={12872-12879},
  keywords={Training;Three-dimensional displays;Semantics;Training data;Data collection;Rendering (computer graphics);Diffusion models;Control systems;Intelligent robots;Autonomous vehicles},
  doi={10.1109/IROS58592.2024.10802002}}
```
