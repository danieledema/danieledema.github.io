+++
date = '2022-05-23T00:00:00Z'
draft = false
title = "Depth-SIMS: Semi-Parametric Image and Depth Synthesis"
tags = ["conference", "generative"]
+++

### Abstract
In this paper we present a compositing image synthesis method that generates RGB canvases with well aligned segmentation maps and sparse depth maps, coupled with an in-painting network that transforms the RGB canvases into high quality RGB images and the sparse depth maps into pixel-wise dense depth maps. We benchmark our method in terms of structural alignment and image quality, showing an increase in mIoU over SOTA by 3.7 percentage points and a highly competitive FID. Furthermore, we analyse the quality of the generated data as training data for semantic segmentation and depth completion, and show that our approach is more suited for this purpose than other methods.

### Useful links
Paper: [https://doi.org/10.1109/icra46639.2022.9811569](https://doi.org/10.1109/icra46639.2022.9811569)

Preprint: [https://arxiv.org/abs/2203.03405](https://arxiv.org/abs/2203.03405)

### Bibtex

``` bibtex
@inproceedings{depthsims2022,
  author={Musat, Valentina and De Martini, Daniele and Gadd, Matthew and Newman, Paul},
  title={Depth-SIMS: Semi-Parametric Image and Depth Synthesis},
  year={2022},
  booktitle={2022 International Conference on Robotics and Automation (ICRA)},
  pages={2388--2394},
  doi={10.1109/icra46639.2022.9811569},
  url={https://doi.org/10.1109/icra46639.2022.9811569},
}
```
