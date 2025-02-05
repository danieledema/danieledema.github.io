+++
date = '2024-03-07T12:07:04Z'
draft = false
title = 'That’s My Point: Compact Object-centric LiDAR Pose Estimation for Large-scale Outdoor Localisation'
tags = ["conference", "pointcloud", "registration", "localisation"]
+++

### Abstract
This paper is about 3D pose estimation on LiDAR scans with extremely minimal storage requirements to enable scalable mapping and localisation.
We achieve this by clustering all points of segmented scans into semantic objects and representing them only with their respective centroid and semantic class.
In this way, each LiDAR scan is reduced to a compact collection of four-number vectors.
This abstracts away important structural information from the scenes, which is crucial for traditional registration approaches.
To mitigate this, we introduce an object-matching network based on self- and cross-correlation that captures geometric and semantic relationships between entities.
The respective matches allow us to recover the relative transformation between scans through weighted Singular Value Decomposition (SVD) and RANdom SAmple Consensus (RANSAC).
We demonstrate that such representation is sufficient for metric localisation by registering point clouds taken under different viewpoints on the KITTI dataset, and at different periods of time localising between KITTI and KITTI-360.
We achieve accurate metric estimates comparable with state-of-the-art methods with almost half the representation size, specifically 1.33 kB on average.

### Useful links
Paper: [https://ieeexplore.ieee.org/document/10611142](https://ieeexplore.ieee.org/document/10611142)

### Bibtex 

``` bibtex
@INPROCEEDINGS{pramatarov2024,
  author={Pramatarov, Georgi and Gadd, Matthew and Newman, Paul and De Martini, Daniele},
  booktitle={2024 IEEE International Conference on Robotics and Automation (ICRA)}, 
  title={That’s My Point: Compact Object-centric LiDAR Pose Estimation for Large-scale Outdoor Localisation}, 
  year={2024},
  volume={},
  number={},
  pages={12276-12282},
  keywords={Point cloud compression;Measurement;Laser radar;Three-dimensional displays;Accuracy;Semantics;Pose estimation;Localisation;Pose Estimation;Semantic Segmentation;Semantic Mapping;Autonomous Vehicles;Robotics},
  doi={10.1109/ICRA57147.2024.10611142}}
```
