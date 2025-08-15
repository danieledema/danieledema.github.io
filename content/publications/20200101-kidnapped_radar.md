+++
date = '2020-08-01T12:00:00Z'
draft = false
title = 'Kidnapped Radar: Topological Radar Localisation using Rotationally-Invariant Metric Learning'
tags = ["conference", "radar", "localisation"]
+++

### Abstract
This paper presents a system for robust, large-scale topological localisation using Frequency-Modulated Continuous-Wave scanning radar which extends the state-of-the-art by an efficient, learning-based approach to handle radar data for localisation. We learn a metric space for embedding polar radar scans using CNN and NetVLAD architectures traditionally applied to the visual domain. However, we tailor the feature extraction for more suitability to the polar nature of radar scan formation using cylindrical convolutions, anti-aliasing blurring, and azimuth-wise max-pooling; all in order to bolster the rotational invariance. The enforced metric space is then used to encode a reference trajectory, serving as a map, which is queried for nearest neighbour for recognition of places at run-time. We demonstrate the performance of our topological localisation system over the course of many repeat forays using the largest radar-focused mobile autonomy dataset released to date, totalling 280 km of urban driving, a small portion of which we also use to learn the weights of the modified architecture. As this work represents a novel application for radar, we analyse the utility of the proposed method via a comprehensive set of metrics which provide insight into the efficacy when used in a realistic system, showing improved performance over the root architecture even in the face of random rotational perturbation.

### Useful links
- [IEEE](https://ieeexplore.ieee.org/abstract/document/9196682)

### Bibtex
```bibtex
@INPROCEEDINGS{9196682,
  author={Săftescu, Ştefan and Gadd, Matthew and De Martini, Daniele and Barnes, Dan and Newman, Paul},
  booktitle={2020 IEEE International Conference on Robotics and Automation (ICRA)}, 
  title={Kidnapped Radar: Topological Radar Localisation using Rotationally-Invariant Metric Learning}, 
  year={2020},
  volume={},
  number={},
  pages={4358-4364},
  keywords={Measurement;Radar imaging;Robot sensing systems;Azimuth;Feature extraction;Trajectory;radar;localisation;place recognition;deep learning;metric learning},
  doi={10.1109/ICRA40945.2020.9196682}}
```
