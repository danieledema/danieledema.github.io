+++
date = '2026-06-04T00:00:00Z'
draft = false
title = "Multi-Robot Planning and Control from CCTV Camera Networks in a Real Warehouse"
tags = ["conference", "graph", "infrastructure"]
+++

### Abstract
Off-board control of mobile robots from cameras embedded in the environment offers a practical path to scalable autonomy, moving sensing and compute off the robots. We extend this idea from the single-robot case to coordinated fleets in a real warehouse, driving multiple robots with only a distributed CCTV network and edge compute. The system operates entirely in image space over an uncalibrated, pixel-wise topological camera graph, enabling wide-area operation with flexible camera placement. A hierarchical planner selects a camera sequence per robot and plans its image-space motion through each view, coordinating robots with a prioritised-then-joint strategy and treating overlapping camera regions as shared resources held by one robot at a time to prevent collisions and deadlocks. We validate the approach in a real warehouse with four robots and 30 cameras across six 27 m aisles, reporting mission times and coordination statistics. To our knowledge, this is the first field demonstration of multi-robot planning and coordination using only an external camera network and off-board compute, with robots carrying no task-specific navigation hardware.

### Useful links
Publication record: [https://ori-mrg.github.io/research/202607-warehouse_inversion/](https://ori-mrg.github.io/research/202607-warehouse_inversion/)

Preprint: [https://arxiv.org/abs/2606.06762](https://arxiv.org/abs/2606.06762)

### Bibtex

``` bibtex
@inproceedings{multirobotcctvwarehouse2026,
  author={Luke Robinson and Benjamin Ramtoula and Anas Izaaryene and Paul Newman and Daniele De Martini},
  title={Multi-Robot Planning and Control from CCTV Camera Networks in a Real Warehouse},
  year={2026},
  booktitle={International Symposium of Robotics Research (ISRR)},
  url={https://ori-mrg.github.io/research/202607-warehouse_inversion/},
  note={ISRR 2026 venue supplied in the author CV; public preprint available},
}
```
