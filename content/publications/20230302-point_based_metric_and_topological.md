+++
date = '2023-03-02T12:07:04Z'
draft = false
title = 'Point-based Metric and Topological Localisation between Lidar and Overhead Imagery'
tags = ["journal", "lidar", "radar", "localisation, "satellite]
+++

### Abstract
In this paper, we present a method for solving the localisation of a ground lidar using overhead imagery only.
Public overhead imagery such as Google satellite images are readily available resources.
They can be used as the map proxy for robot localisation, relaxing the requirement for a prior traversal for mapping as in traditional approaches.
While prior approaches have focused on the metric localisation between range sensors and overhead imagery, our method is the first to learn both place recognition and metric localisation of a ground lidar using overhead imagery, and also outperforms prior methods on metric localisation with large initial pose offsets.
To bridge the drastic domain gap between lidar data and overhead imagery, our method learns to transform an overhead image into a collection of 2D points, emulating the resulting point-cloud scanned by a lidar sensor situated near the centre of the overhead image.
After both modalities are expressed as point sets, point-based machine learning methods for localisation are applied.

### Useful links
Paper: [https://link.springer.com/article/10.1007/s10514-023-10085-w](https://link.springer.com/article/10.1007/s10514-023-10085-w)

### Bibtex 

``` bibtex
@article{tang2023point,
  title={Point-based metric and topological localisation between lidar and overhead imagery},
  author={Tang, Tim Yuqing and De Martini, Daniele and Newman, Paul},
  journal={Autonomous Robots},
  volume={47},
  number={5},
  pages={595--615},
  year={2023},
  publisher={Springer}
}
```
