+++
date = '2023-10-01T12:07:04Z'
draft = false
title = 'Visual Servoing on Wheels: Robust Robot Orientation Estimation in Remote Viewpoint Control'
tags = ["conference", "inversion", "infrastruture"]
+++

### Abstract
This work proposes a fast deployment pipeline for visually-servoed robots which does not assume anything about either the robot - e.g. sizes, colour or the presence of markers - or the deployment environment.
Specifically, we apply a learning based approach to reliably estimate the pose of a robot in the image frame of a 2D camera upon which a visual servoing control system can be deployed.
To alleviate the time-consuming process of labelling image data, we propose a weakly supervised pipeline that can produce a vast amount of data in a small amount of time.
We evaluate our approach on a dataset of remote camera images captured in various indoor environments demonstrating high tracking performances when integrated into a fully-autonomous pipeline with a simple controller.
With this, we then analyse the data requirement of our approach, showing how it is possible to deploy a new robot in a new environment in fewer than 30.00 min.

### Useful links
Paper: [https://ieeexplore.ieee.org/abstract/document/10341260](https://ieeexplore.ieee.org/abstract/document/10341260)

### Bibtex 

``` bibtex
@INPROCEEDINGS{robinson2023,
  author={Robinson, Luke and De Martini, Daniele and Gadd, Matthew and Newman, Paul},
  booktitle={2023 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)}, 
  title={Visual Servoing on Wheels: Robust Robot Orientation Estimation in Remote Viewpoint Control}, 
  year={2023},
  volume={},
  number={},
  pages={6364-6370},
  keywords={Training;Visualization;Pipelines;Wheels;Cameras;Visual servoing;Mobile robots;Cloud Robotics;Visual Servoing;Deep Learning},
  doi={10.1109/IROS55552.2023.10341260}}
```
