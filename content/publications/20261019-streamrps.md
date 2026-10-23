+++
date = '2026-10-19T00:00:00Z'
draft = false
title = "Real-Time Radar Semantic and Panoptic Scene Understanding"
tags = ["preprint", "radar"]
+++

### Abstract
Robust scene understanding under varying environmental conditions is essential for safe autonomous driving. While cameras and LiDAR degrade in adverse weather and poor lighting, Frequency-Modulated Continuous-Wave (FMCW) spinning radar provides dependable 360° perception at extended ranges with minimal compute cost. However, real-time FMCW radar scene understanding is challenging due to complex signal returns, limited temporal resolution, and scarce annotated datasets. We introduce StreamRPS, a novel framework for streaming FMCW radar panoptic segmentation, comprising an automated label-generation pipeline via LiDAR scene completion and a real-time streaming network for semantic and panoptic segmentation. Our encoder-decoder streaming architecture comprises a radar-specific hierarchical Transformer encoder and task-specific decoders for semantic or panoptic prediction. Our encoder introduces a stem to capture range-dependent signatures, anisotropic patch embeddings to preserve angular resolution, and axial polar attention to separately model the periodic azimuth and bounded range axes. We further introduce azimuth roll rotation augmentation to simulate ego-vehicle rotation during training. Comprehensive experiments on the SAX and BOREAS datasets validate both our auto-labeling methodology and streaming segmentation network against established baselines. We outperform the strongest baseline by at least 1.4pp while processing sectors at over 400 FPS in a 4-sector streaming setting. We additionally provide manual annotations for 100 SAX radar scans, enabling independent evaluation of the entire framework.

### Useful links
Paper: [https://arxiv.org/abs/2610.26816](https://arxiv.org/abs/2610.26816)

### Bibtex

``` bibtex
@misc{streamrps2026,
  author={Santosh Parit and Julia Hindel and Rohit Mohan and Georgi Pramatarov and Paul Newman and Daniele De Martini and Abhinav Valada},
  title={Real-Time Radar Semantic and Panoptic Scene Understanding},
  year={2026},
  eprint={2610.26816},
  archivePrefix={arXiv},
  url={https://arxiv.org/abs/2610.26816},
}
```
