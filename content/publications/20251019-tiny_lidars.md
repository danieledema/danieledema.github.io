+++
date = '2025-10-19T00:00:00Z'
draft = false
title = "Tiny LiDARs for Manipulator Self-Awareness: Sensor Characterization and Initial Localization Experiments"
tags = ["conference", "localisation", "uncertainty"]
+++

### Abstract
For several tasks, ranging from manipulation to inspection, it is beneficial for robots to localize a target object in their surroundings. In this paper, we propose an approach that utilizes coarse point clouds obtained from miniaturized VL53L5CX Time-of-Flight (ToF) sensors (tiny LiDARs) to localize a target object in the robot's workspace. We first conduct an experimental campaign to calibrate the dependency of sensor readings on relative range and orientation to targets. We then propose a probabilistic sensor model, which we validate in an object pose estimation task using a Particle Filter (PF). The results show that the proposed sensor model improves the performance of the localization of the target object with respect to two baselines: one that assumes measurements are free from uncertainty and one in which the confidence is provided by the sensor datasheet.

### Useful links
Paper: [https://doi.org/10.1109/iros60139.2025.11246575](https://doi.org/10.1109/iros60139.2025.11246575)

Preprint: [https://arxiv.org/abs/2503.03449](https://arxiv.org/abs/2503.03449)

### Bibtex

``` bibtex
@inproceedings{tinylidars2025,
  author={Caroleo, Giammarco and Albini, Alessandro and De Martini, Daniele and Barfoot, Timothy D. and Maiolino, Perla},
  title={Tiny LiDARs for Manipulator Self-Awareness: Sensor Characterization and Initial Localization Experiments},
  year={2025},
  booktitle={2025 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)},
  pages={12940--12946},
  doi={10.1109/iros60139.2025.11246575},
  url={https://doi.org/10.1109/iros60139.2025.11246575},
}
```
