+++
date = '2026-05-18T00:00:00Z'
draft = false
title = "RGB-only Active 3D Scene Graph Generation for Indoor Mobile Robots"
tags = ["workshop", "graph", "infrastructure"]
+++

### Abstract
Current approaches to 3D scene graph generation rely on dedicated depth sensors, such as LiDAR or RGB-D cameras, for metric 3D reconstruction. This limits deployment to specialized robotic platforms and excludes settings where only RGB cameras are available, such as fixed external infrastructure. Existing pipelines also typically operate on passively collected observation trajectories, rather than selecting viewpoints based on the partially built scene representation, and therefore fail to effectively exploit the semantic and spatial information encoded within the graph during exploration. This paper presents a fully visual framework for the active, incremental construction of 3D scene graphs from RGB input only, addressing both limitations. The proposed approach unifies perception and planning around a shared structured representation that captures object semantics, 3D geometry, relational context, and information from multiple viewpoints. Because the framework is hardware-agnostic and relies only on RGB observations, it can incorporate inputs from both onboard robot cameras and fixed external cameras within the same representation. Experiments on the Replica dataset show that the RGB-only pipeline achieves F1-score parity with baselines using ground-truth depth. Active exploration experiments on ReplicaCAD further show that semantic-driven viewpoint selection detects more than twice as many objects as a geometric frontier-based baseline under the same exploration budget. Finally, the external-camera setting demonstrates that complementary RGB views can effectively bootstrap the scene graph and improve contextual understanding at no additional exploration cost.

### Useful links
Preprint: [https://arxiv.org/abs/2605.18197](https://arxiv.org/abs/2605.18197)

### Bibtex

``` bibtex
@inproceedings{rgbactivescenegraphs2026,
  author={Giorgia Modi and Davide Buoso and Giuseppe Averta and Daniele De Martini},
  title={RGB-only Active 3D Scene Graph Generation for Indoor Mobile Robots},
  year={2026},
  booktitle={ICRA Workshop on Semantics for Reliable Robot Autonomy},
  url={https://arxiv.org/abs/2605.18197},
}
```
