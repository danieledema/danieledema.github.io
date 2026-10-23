+++
date = '2021-11-04T00:00:00Z'
draft = false
title = "Unsupervised Change Detection of Extreme Events Using ML On-Board"
tags = ["workshop", "satellite"]
+++

### Abstract
In this paper, we introduce RaVAEn, a lightweight, unsupervised approach for change detection in satellite data based on Variational Auto-Encoders (VAEs) with the specific purpose of on-board deployment. Applications such as disaster management enormously benefit from the rapid availability of satellite observations. Traditionally, data analysis is performed on the ground after all data is transferred - downlinked - to a ground station. Constraint on the downlink capabilities therefore affects any downstream application. In contrast, RaVAEn pre-processes the sampled data directly on the satellite and flags changed areas to prioritise for downlink, shortening the response time. We verified the efficacy of our system on a dataset composed of time series of catastrophic events - which we plan to release alongside this publication - demonstrating that RaVAEn outperforms pixel-wise baselines. Finally we tested our approach on resource-limited hardware for assessing computational and memory limitations.

### Useful links
Preprint: [https://arxiv.org/abs/2111.02995](https://arxiv.org/abs/2111.02995)

### Bibtex

``` bibtex
@inproceedings{ravenworkshop2021,
  author={Vít Růžička and Anna Vaughan and Daniele De Martini and James Fulton and Valentina Salvatelli and Chris Bridges and Gonzalo Mateo-Garcia and Valentina Zantedeschi},
  title={Unsupervised Change Detection of Extreme Events Using ML On-Board},
  year={2021},
  booktitle={NeurIPS Workshop on Artificial Intelligence for Humanitarian Assistance and Disaster Response (AI+HADR)},
  url={https://arxiv.org/abs/2111.02995},
}
```
