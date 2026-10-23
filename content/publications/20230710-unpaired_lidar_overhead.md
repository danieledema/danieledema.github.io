+++
date = '2023-07-10T00:00:00Z'
draft = false
title = "Self-Supervised Lidar Place Recognition in Overhead Imagery Using Unpaired Data"
tags = ["conference", "localisation", "satellite"]
+++

### Abstract
As much as place recognition is crucial for navigation, mapping and collecting training ground truth, namely sensor data pairs across different locations, are costly and time-consuming. This paper tackles these by learning lidar place recognition on public overhead imagery and in a self-supervised fashion, with no need for paired lidar and overhead imagery data. We learn the cross-modal data comparison between lidar and overhead imagery with a multi-step framework. First, images are transformed into synthetic lidar data and a latent projection is learned. Next, we discover pseudo pairs of lidar and satellite data from unpaired and asynchronous sequences, and use them for training a final embedding space projection in a cross-modality place recognition framework. We train and test our approach on real data from various environments and show performances approaching a supervised method using paired data.

### Useful links
Paper: [https://doi.org/10.15607/rss.2023.xix.098](https://doi.org/10.15607/rss.2023.xix.098)

Publication record: [https://www.roboticsproceedings.org/rss19/p098.html](https://www.roboticsproceedings.org/rss19/p098.html)

### Bibtex

``` bibtex
@inproceedings{unpairedlidaroverhead2023,
  author={Tang, Tim and Martini, Daniele and Newman, Paul},
  title={Self-Supervised Lidar Place Recognition in Overhead Imagery Using Unpaired Data},
  year={2023},
  booktitle={Robotics: Science and Systems XIX},
  doi={10.15607/rss.2023.xix.098},
  url={https://doi.org/10.15607/rss.2023.xix.098},
}
```
