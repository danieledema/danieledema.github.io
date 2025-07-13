+++
date = '2022-10-08T12:00:00Z'
draft = false
title = 'RaVÆn: unsupervised change detection of extreme events using ML on-board satellites'
tags = ["journal", "satellite", "machine-learning"]
+++

### Abstract
Applications such as disaster management enormously benefit from rapid availability of satellite observations.
Traditionally, data analysis is performed on the ground after being transferred—downlinked—to a ground station.
Constraints on the downlink capabilities, both in terms of data volume and timing, therefore heavily affect the response delay of any downstream application.
In this paper, we introduce RaVÆn, a lightweight, unsupervised approach for change detection in satellite data based on Variational Auto-Encoders (VAEs), with the specific purpose of on-board deployment.
RaVÆn pre-processes the sampled data directly on the satellite and flags changed areas to prioritise for downlink, shortening the response time.
We verified the efficacy of our system on a dataset—which we release alongside this publication—composed of time series containing a catastrophic event, demonstrating that RaVÆn outperforms pixel-wise baselines.
Finally, we tested our approach on resource-limited hardware for assessing computational and memory limitations, simulating deployment on real hardware.

### Useful links
Paper: [https://www.nature.com/articles/s41598-022-19437-5](https://www.nature.com/articles/s41598-022-19437-5)

### Bibltex

```bibtex
@article{ruuvzivcka2022ravaen,
  title={RaV{\AE}n: unsupervised change detection of extreme events using ML on-board satellites},
  author={R{\uu}{\v{z}}i{\v{c}}ka, V{\'\i}t and Vaughan, Anna and De Martini, Daniele and Fulton, James and Salvatelli, Valentina and Bridges, Chris and Mateo-Garcia, Gonzalo and Zantedeschi, Valentina},
  journal={Scientific reports},
  volume={12},
  number={1},
  pages={16939},
  year={2022},
  publisher={Nature Publishing Group UK London}
}
```
