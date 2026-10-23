+++
date = '2021-01-01T00:00:00Z'
draft = false
title = "Smart satellites: machine learning on-board for low-latency novelty detection"
tags = ["workshop", "satellite"]
# Only the publication year is known; the first day is used for chronological sorting.
+++

### Abstract
Satellite observations of the Earth’s surface provide a vital data source for diverse environmental applications including disaster management, detection of landcover change and ecological monitoring. Currently, sensors on satellites collect and downlink all data points for further processing on the ground. Limitations in downlink capacity and speed result in delays in data availability on the ground. This particularly affects applications such as disaster management which require data as quickly as possible for online event monitoring. This problem is set to worsen as the sensing resolution and number of satellites in orbit increase.

A solution is to pre-process incoming data on-board the satellite using machine learning. In this scenario, the most useful information for a particular application is identified on-board, then prioritised for rapid downlink. Existing work has focused on the deployment of supervised classifiers for applications such as identifying floods. Supervised learning has a major drawback: only events of a particular type determined at training time will be flagged as interesting and prioritised for downlink, with no generalisation to new event types, imager specifications, and lighting or local features.

We propose a new fully unsupervised novelty-detection model suitable for deployment on remote sensing platforms. A variational autoencoder is used to generate a latent representation of incoming sensor data over a particular region. A novelty score is assigned to a specific location using the distance between its latent representation of consecutive passes. This method has the advantage that any change between passes can be detected on-board at inference time.

We evaluate the performance of this model detecting changes in land-surface observations from the Sentinel-2 Multispectral Instrument on several time series of natural disaster datasets including floods, landslides, wildfires and hurricanes. The unsupervised novelty detection model is demonstrated to assign higher novelty scores to regions of known change, and outperforms computer-vision image differencing baselines. We further demonstrate via experiments on constrained Xilinx Pynq hardware that this model is suitable for deployment on a remote sensing platform.

### Useful links
Publication record: [https://eslab.ai/publications](https://eslab.ai/publications)

### Bibtex

``` bibtex
@inproceedings{smartsatellitesagu2021,
  author={Růžička, V. and Vaughan, A. and De Martini, D. and Fulton, J. and Salvatelli, V. and Bridges, C. and Mateo-Garcia, G. and Zantedeschi, V.},
  title={Smart satellites: machine learning on-board for low-latency novelty detection},
  year={2021},
  booktitle={AGU Fall Meeting},
  url={https://eslab.ai/publications},
}
```
