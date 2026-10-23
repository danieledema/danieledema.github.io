+++
date = '2021-07-12T00:00:00Z'
draft = false
title = "Get to the Point: Learning Lidar Place Recognition and Metric Localisation Using Overhead Imagery"
tags = ["conference", "localisation", "satellite"]
+++

### Abstract
This paper is about localising a robot in overhead images using lidar. Specifically; we show how to solve both place recognition and metric localisation of a lidar using only publicly available overhead imagery as a map proxy. This is in contrast to current approaches that rely on prior sensor maps. To handle the drastic modality difference (overhead image vs. on the ground lidar); our method learns a representation that purposely and suitably transforms a given overhead image into a collection of 2D points; allowing for direct comparison against lidar scans. After both modalities are expressed as points; point-based methods can then be leveraged to learn the registration and place recognition task. Our method is the first to learn the place recognition of a lidar using only overhead imagery; and outperforms prior work for metric localisation with large initial pose offsets.

### Useful links
Paper: [https://doi.org/10.15607/rss.2021.xvii.003](https://doi.org/10.15607/rss.2021.xvii.003)

Publication record: [https://www.roboticsproceedings.org/rss17/p003.html](https://www.roboticsproceedings.org/rss17/p003.html)

### Bibtex

``` bibtex
@inproceedings{gettothepoint2021,
  author={Tang, Tim and De Martini, Daniele and Newman, Paul},
  title={Get to the Point: Learning Lidar Place Recognition and Metric Localisation Using Overhead Imagery},
  year={2021},
  booktitle={Robotics: Science and Systems XVII},
  doi={10.15607/rss.2021.xvii.003},
  url={https://doi.org/10.15607/rss.2021.xvii.003},
}
```
