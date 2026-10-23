+++
date = '2025-11-18T00:00:00Z'
draft = false
title = "Ensemble of Pre-Trained Models for Long-Tailed Trajectory Prediction"
tags = ["conference"]
+++

### Abstract
This work explores the application of ensemble modeling to the multidimensional regression problem of trajectory prediction for vehicles in urban environments. As newer and bigger state-of-the-art prediction models for autonomous driving continue to emerge, an important open challenge is the problem of how to combine the strengths of these big models without the need for costly re-training. We show how, perhaps surprisingly, combining state-of-the-art deep learning models out-of-the-box (without retraining or fine-tuning) with a simple confidence-weighted average method can enhance the overall prediction. Indeed, while combining trajectory prediction models is not straightforward, this simple approach enhances performance by 10% over the best prediction model, especially in the long-tailed metrics. We show that this performance improvement holds on both the NuScenes and Argoverse datasets, and that these improvements are made across the dataset distribution. The code for our work is open source.

### Useful links
Paper: [https://doi.org/10.1109/itsc60802.2025.11423305](https://doi.org/10.1109/itsc60802.2025.11423305)

Preprint: [https://arxiv.org/abs/2509.13914](https://arxiv.org/abs/2509.13914)

### Bibtex

``` bibtex
@inproceedings{ensembletrajectoryprediction2025,
  author={Thuremella, Divya and Yang, Yi and Wanna, Simon and Kunze, Lars and De Martini, Daniele},
  title={Ensemble of Pre-Trained Models for Long-Tailed Trajectory Prediction},
  year={2025},
  booktitle={2025 IEEE 28th International Conference on Intelligent Transportation Systems (ITSC)},
  pages={2055--2062},
  doi={10.1109/itsc60802.2025.11423305},
  url={https://doi.org/10.1109/itsc60802.2025.11423305},
}
```
