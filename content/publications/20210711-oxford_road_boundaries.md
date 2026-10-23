+++
date = '2021-07-11T00:00:00Z'
draft = false
title = "The Oxford Road Boundaries Dataset"
tags = ["workshop", "dataset"]
+++

### Abstract
In this paper we present the Oxford Road Boundaries Dataset, designed for training and testing machine-learning-based road-boundary detection and inference approaches. We have hand-annotated two of the 10 km-long forays from the Oxford Robotcar Dataset and generated from other forays several thousand further examples with semi-annotated road-boundary masks. To boost the number of training samples in this way, we used a vision-based localiser to project labels from the annotated datasets to other traversals at different times and weather conditions. As a result, we release 62605 labelled samples, of which 47639 samples are curated. Each of these samples contains both raw and classified masks for left and right lenses. Our data contains images from a diverse set of scenarios such as straight roads, parked cars, junctions, etc. Files for download and tools for manipulating the labelled data are available at: oxford-robotics-institute.github.io/road-boundaries-dataset

### Useful links
Paper: [https://doi.org/10.1109/ivworkshops54471.2021.9669250](https://doi.org/10.1109/ivworkshops54471.2021.9669250)

Preprint: [https://arxiv.org/abs/2106.08983](https://arxiv.org/abs/2106.08983)

Dataset: [https://oxford-robotics-institute.github.io/road-boundaries-dataset/](https://oxford-robotics-institute.github.io/road-boundaries-dataset/)

### Bibtex

``` bibtex
@inproceedings{oxfordroadboundaries2021,
  author={Suleymanov, Tarlan and Gadd, Matthew and De Martini, Daniele and Newman, Paul},
  title={The Oxford Road Boundaries Dataset},
  year={2021},
  booktitle={2021 IEEE Intelligent Vehicles Symposium Workshops (IV Workshops)},
  pages={222--227},
  doi={10.1109/ivworkshops54471.2021.9669250},
  url={https://doi.org/10.1109/ivworkshops54471.2021.9669250},
}
```
