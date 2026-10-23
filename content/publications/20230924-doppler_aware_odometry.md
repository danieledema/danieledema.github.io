+++
date = '2023-09-24T00:00:00Z'
draft = false
title = "Doppler-Aware Odometry from FMCW Scanning Radar"
tags = ["conference", "radar"]
+++

### Abstract
This work explores Doppler information from a millimetre-Wave (mm-W) Frequency-Modulated Continuous-Wave (FMCW) scanning radar to make odometry estimation more robust and accurate. Firstly, doppler information is added to the scan masking process to enhance correlative scan matching. Secondly, we train a Neural Network (NN) for regressing forward velocity directly from a single radar scan; we fuse this estimate with the correlative scan matching estimate and show improved robustness to bad estimates caused by challenging environment geometries, e.g. narrow tunnels. We test our method with a novel custom dataset which is released with this work at https://ori.ox.ac.uk/publications/datasets.

### Useful links
Paper: [https://doi.org/10.1109/itsc57777.2023.10422412](https://doi.org/10.1109/itsc57777.2023.10422412)

Preprint: [https://arxiv.org/abs/2308.10597](https://arxiv.org/abs/2308.10597)

### Bibtex

``` bibtex
@inproceedings{dopplerawareodometry2023,
  author={Rennie, Fraser and Williams, David and Newman, Paul and De Martini, Daniele},
  title={Doppler-Aware Odometry from FMCW Scanning Radar},
  year={2023},
  booktitle={2023 IEEE 26th International Conference on Intelligent Transportation Systems (ITSC)},
  pages={5126--5132},
  doi={10.1109/itsc57777.2023.10422412},
  url={https://doi.org/10.1109/itsc57777.2023.10422412},
}
```
