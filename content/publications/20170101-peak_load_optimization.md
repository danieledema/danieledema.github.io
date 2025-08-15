+++
date = '2017-09-01T00:00:00Z'
draft = false
title = 'Peak load optimization through 2-dimensional packing and multi-processor real-time scheduling'
tags = ["conference", "optimization", "scheduling"]
+++

### Abstract
The use of real-time scheduling methods to coordinate a set of power loads is being explored in the field of Cyber-Physical Energy Systems, with the goal of optimizing the aggregated peak load of power used by many electric loads. Real-time scheduling has attractive features in this domain. Thanks to its inherent resource optimization, which limits the number of concurrent tasks that are running at the same time, real-time scheduling provides direct benefits to peak load optimization.
This paper shows the combined use of a two-dimensional bin-packing method and an optimal multi-processor real-time scheduling algorithm to coordinate the activation of electric loads. The result is an effective global scheduling approach where the activation of loads is organized into a pattern that takes into account the timing constraints of the loads and the actual combination of active loads. The validation is done by scheduling a set of thermal loads (heaters) in a building, with accurately modeled temperature dynamics. The proposed method is shown to achieve a significant peak load reduction, up to around 70%, w.r.t. the traditional thermostat controller.

### Useful links
Paper: [https://dl.acm.org/doi/10.1145/3075564.3075587](https://dl.acm.org/doi/10.1145/3075564.3075587)

### Bibtex
```bibtex
@inproceedings{10.1145/3075564.3075587,
author = {De Martini, Daniele and Benetti, Guido and Cipolla, Filippo and Caprino, Davide and Vedova, Marco L. Delia and Facchinetti, Tullio},
title = {Peak load optimization through 2-dimensional packing and multi-processor real-time scheduling},
year = {2017},
isbn = {9781450344876},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3075564.3075587},
doi = {10.1145/3075564.3075587},
booktitle = {Proceedings of the Computing Frontiers Conference},
pages = {275–278},
numpages = {4},
keywords = {Thermal systems, Smart grid, Real-time scheduling, Power management, Planning and scheduling, Peak load shaving, Partitioned scheduling, Hybrid switching systems, First-fit decreasing height, Dynamical systems, Direct-load control, Demand-side management, Cyber-Physical Energy Systems, Bin-packing, Adaptive scheduling},
location = {Siena, Italy},
series = {CF'17}
}
```