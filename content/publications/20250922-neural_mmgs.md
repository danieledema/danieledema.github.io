+++
date = '2025-09-22T00:00:00Z'
draft = false
title = "Neural-MMGS: Multi-modal Neural Gaussian Splats for Large-Scale Scene Reconstruction"
tags = ["preprint", "generative"]
+++

### Abstract
This paper proposes Neural-MMGS, a novel neural 3DGS framework for multimodal large-scale scene reconstruction that fuses multiple sensing modalities in a per-gaussian compact, learnable embedding. While recent works focusing on large-scale scene reconstruction have incorporated LiDAR data to provide more accurate geometric constraints, we argue that LiDAR's rich physical properties remain underexplored. Similarly, semantic information has been used for object retrieval, but could provide valuable high-level context for scene reconstruction. Traditional approaches append these properties to Gaussians as separate parameters, increasing memory usage and limiting information exchange across modalities. Instead, our approach fuses all modalities -- image, LiDAR, and semantics -- into a compact, learnable embedding that implicitly encodes optical, physical, and semantic features in each Gaussian. We then train lightweight neural decoders to map these embeddings to Gaussian parameters, enabling the reconstruction of each sensing modality with lower memory overhead and improved scalability. We evaluate Neural-MMGS on the Oxford Spires and KITTI-360 datasets. On Oxford Spires, we achieve higher-quality reconstructions, while on KITTI-360, our method reaches competitive results with less storage consumption compared with current approaches in LiDAR-based novel-view synthesis.

### Useful links
Paper: [https://arxiv.org/abs/2509.17762](https://arxiv.org/abs/2509.17762)

### Bibtex

``` bibtex
@misc{neuralmmgs2025,
  author={Sitian Shen and Georgi Pramatarov and Yifu Tao and Daniele De Martini},
  title={Neural-MMGS: Multi-modal Neural Gaussian Splats for Large-Scale Scene Reconstruction},
  year={2025},
  eprint={2509.17762},
  archivePrefix={arXiv},
  url={https://arxiv.org/abs/2509.17762},
}
```
