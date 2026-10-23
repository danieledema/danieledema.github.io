+++
date = '2021-09-28T00:00:00Z'
draft = false
title = "Self-supervised learning for using overhead imagery as maps in outdoor range sensor localization"
tags = ["journal", "radar", "localisation", "satellite"]
+++

### Abstract
Traditional approaches to outdoor vehicle localization assume a reliable, prior map is available, typically built using the same sensor suite as the on-board sensors used during localization. This work makes a different assumption. It assumes that an overhead image of the workspace is available and utilizes that as a map for use for range-based sensor localization by a vehicle. Here, range-based sensors are radars and lidars. Our motivation is simple, off-the-shelf, publicly available overhead imagery such as Google satellite images can be a ubiquitous, cheap, and powerful tool for vehicle localization when a usable prior sensor map is unavailable, inconvenient, or expensive. The challenge to be addressed is that overhead images are clearly not directly comparable to data from ground range sensors because of their starkly different modalities. We present a learned metric localization method that not only handles the modality difference, but is also cheap to train, learning in a self-supervised fashion without requiring metrically accurate ground truth. By evaluating across multiple real-world datasets, we demonstrate the robustness and versatility of our method for various sensor configurations in cross-modality localization, achieving localization errors on-par with a prior supervised approach while requiring no pixel-wise aligned ground truth for supervision at training. We pay particular attention to the use of millimeter-wave radar, which, owing to its complex interaction with the scene and its immunity to weather and lighting conditions, makes for a compelling and valuable use case.

### Useful links
Paper: [https://doi.org/10.1177/02783649211045736](https://doi.org/10.1177/02783649211045736)

### Bibtex

``` bibtex
@article{overheadimagerylocalisationijrr2021,
  author={Tang, Tim Y. and De Martini, Daniele and Wu, Shangzhe and Newman, Paul},
  title={Self-supervised learning for using overhead imagery as maps in outdoor range sensor localization},
  year={2021},
  journal={The International Journal of Robotics Research},
  volume={40},
  number={12-14},
  pages={1488--1509},
  doi={10.1177/02783649211045736},
  url={https://doi.org/10.1177/02783649211045736},
}
```
