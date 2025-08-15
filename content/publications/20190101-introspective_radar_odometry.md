+++
date = '2019-10-01T12:00:00Z'
draft = false
title = 'What Could Go Wrong? Introspective Radar Odometry in Challenging Environments'
tags = ["conference", "radar", "odometry"]
+++

### Abstract
This paper is about detecting failures under uncertainty and improving the reliability of radar-only motion estimation. We use weak supervision together with inertial measurement fusion to train a classifier that exploits the principal eigenvector associated with our radar scan matching algorithm at run-time and produces a prior belief in the robot's motion estimate. This prior is used in a filtering framework to correct for vehicle motion estimates. We demonstrate the system on a challenging outdoor dataset, for which current radar motion estimation algorithms fail frequently. By knowing when failure is likely, we achieve qualitatively superior motion estimates and quantitatively fewer odometry failures. Specifically, we see 24.7 % fewer failures in motion estimation over the course of a 15.81 km drive through a difficult, mixed rural-and-urban scene, with lower RMSE in translational and rotational estimates during particularly challenging conditions.

### Useful links
Paper: [Paper on IEEE Xplore](https://ieeexplore.ieee.org/document/8917111/)

### Bibtex
```bibtex
@INPROCEEDINGS{8917111,
  author={Aldera, Roberto and Martini, Daniele De and Gadd, Matthew and Newman, Paul},
  booktitle={2019 IEEE Intelligent Transportation Systems Conference (ITSC)}, 
  title={What Could Go Wrong? Introspective Radar Odometry in Challenging Environments}, 
  year={2019},
  volume={},
  number={},
  pages={2835-2842},
  keywords={Radar measurements;Global Positioning System;Motion estimation;Robot sensing systems;Robustness;radar;sensing;ego-motion estimation;introspection;field robotics},
  doi={10.1109/ITSC.2019.8917111}}
```
