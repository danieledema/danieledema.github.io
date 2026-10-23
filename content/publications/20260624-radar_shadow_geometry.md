+++
date = '2026-06-24T00:00:00Z'
draft = false
title = "Beyond a Shadow of a Doubt: Close Proximity Geometry Reconstruction Using FMCW Radar Shadow Effects"
tags = ["preprint", "radar"]
+++

### Abstract
Reliable perception in adverse conditions remains challenging for autonomous systems, as cameras and LiDAR degrade in poor lighting or weather. Millimetre-wave FMCW radar is robust to such conditions, but its elevation collapse limits geometric reasoning. We observe that vehicle chassis occlude radar rays and form a distinctive geometric shadow, and its consistency can enable us to infer useful information about objects whose returns intersect this shadow. Motivated by this observation, we propose a method to recover the 3D, in-plane inclination of nearby slender vertical objects from this cue. The object inclination is retrieved without assumptions about the wider scene, but through an analytical, closed-form mapping between its radar return boundaries and the opening angle. Validation in simulation and experimentation on a Navtech CTS350-X radar shows that inclinations can be estimated under practical conditions, with segmentation of the object in the radar scan emerging as the main bottleneck. This work highlights chassis shadows as a novel geometric cue, extending the role of 2D rotating radar beyond localisation and toward 3D scene reconstruction.

### Useful links
Paper: [https://arxiv.org/abs/2606.25829](https://arxiv.org/abs/2606.25829)

### Bibtex

``` bibtex
@misc{radarshadowgeometry2026,
  author={Felix de Trogoff du Boisguezennec and Benjamin Ramtoula and Daniele De Martini},
  title={Beyond a Shadow of a Doubt: Close Proximity Geometry Reconstruction Using FMCW Radar Shadow Effects},
  year={2026},
  eprint={2606.25829},
  archivePrefix={arXiv},
  url={https://arxiv.org/abs/2606.25829},
}
```
