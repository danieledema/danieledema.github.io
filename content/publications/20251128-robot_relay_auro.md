+++
date = '2025-11-28T00:00:00Z'
draft = false
title = "Robot-relay: building-wide, calibration-less visual servoing with learned sensor handover networks"
tags = ["journal", "infrastructure"]
+++

### Abstract
This paper proposes a novel system to conduct visual servoing of a mobile robot using multiple uncalibrated, wall-mounted cameras. Specifically, we utilise a constellation of such sensors to cover a wide area by allowing robot control to be passed between cameras in regions where their fields of view overlap. This method, in conjunction with the fact that all computing is also executed offboard, allows for simpler and cheaper robots to be deployed in controlled and finite spaces. Our method simplifies the natural installation cycle of a newly deployed camera network, eliminating the need for explicit camera positioning or orientation, both globally (relative to a building plan) and locally (among viewpoints). Our system memorises pixel-wise topological connections between viewpoints by leveraging natural human exploration of the environment. We detect graph edges through simultaneous detections of the same person across different cameras, allowing us to automatically construct an evolving graph that represents overlapping fields of view within the camera network. In combination with a hybrid-A*-based planner, our approach allows efficient planning and control of robots across a wide area by traversing cameras between areas of overlap. We validate our approach through autonomous traversals in a productive office environment, using a network of six cameras, and compare our performance against both human teleoperation and a traditional Simultaneous Localisation and Mapping (SLAM) approach.

### Useful links
Earlier conference version: [ISER 2023](/publications/20231126-robot_relay/)

Paper: [https://doi.org/10.1007/s10514-025-10227-2](https://doi.org/10.1007/s10514-025-10227-2)

Earlier conference preprint: [https://arxiv.org/abs/2310.15677](https://arxiv.org/abs/2310.15677)

### Bibtex

``` bibtex
@article{robotrelayauro2026,
  author={Robinson, Luke and Gadd, Matthew and Newman, Paul and De Martini, Daniele},
  title={Robot-relay: building-wide, calibration-less visual servoing with learned sensor handover networks},
  year={2026},
  journal={Autonomous Robots},
  volume={50},
  number={1},
  pages={3},
  doi={10.1007/s10514-025-10227-2},
  url={https://doi.org/10.1007/s10514-025-10227-2},
  note={First published online on 28 November 2025},
}
```
