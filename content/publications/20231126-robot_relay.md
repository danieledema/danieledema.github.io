+++
date = '2023-11-26T12:07:04Z'
draft = false
title = 'Robot-Relay:Building-Wide, Calibration-Less Visual Servoing with Learned Sensor Handover Networks'
tags = ["conference", "graph", "inversion", "infrastructure"]
+++

### Abstract
We present a system which grows and manages a network of remote viewpoints during the natural installation cycle for a newly installed camera network or a newly deployed robot fleet.
No explicit notion of camera position or orientation is required, neither global – i.e. relative to a building plan – nor local – i.e. relative to an interesting point in a room.
Furthermore, no metric relationship between viewpoints is required.
Instead, we leverage our prior work in effective remote control without extrinsic or intrinsic calibration and extend it to the multi-camera setting.
In this, we memorise, from simultaneous robot detections in the tracker thread, soft pixel-wise topological connections between viewpoints.
We demonstrate our system with repeated autonomous traversals of workspaces connected by a network of six cameras across a productive office environment

### Useful links
Paper: [https://link.springer.com/chapter/10.1007/978-3-031-63596-0_12](https://link.springer.com/chapter/10.1007/978-3-031-63596-0_12)

### Bibtex 

``` bibtex
@INPROCEEDINGS{robinson2023,
author="Robinson, Luke and Gadd, Matthew and Newman, Paul and Martini, Daniele De",
editor="Ang Jr, Marcelo H. and Khatib, Oussama",
title="Robot-Relay:Building-Wide, Calibration-Less Visual Servoing with Learned Sensor Handover Networks",
booktitle="Experimental Robotics",
year="2024",
publisher="Springer Nature Switzerland",
address="Cham",
pages="129--140",
abstract="We present a system which grows and manages a network of remote viewpoints during the natural installation cycle for a newly installed camera network or a newly deployed robot fleet. No explicit notion of camera position or orientation is required, neither global -- i.e. relative to a building plan -- nor local -- i.e. relative to an interesting point in a room. Furthermore, no metric relationship between viewpoints is required. Instead, we leverage our prior work in effective remote control without extrinsic or intrinsic calibration and extend it to the multi-camera setting. In this, we memorise, from simultaneous robot detections in the tracker thread, soft pixel-wise topological connections between viewpoints. We demonstrate our system with repeated autonomous traversals of workspaces connected by a network of six cameras across a productive office environment.",
isbn="978-3-031-63596-0"
}
```
