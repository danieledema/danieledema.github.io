+++
date = '2025-12-01T00:00:00Z'
draft = false
title = "Fantastic Features and Where to Find Them: A Probing Method to combine Features from Multiple Foundation Models"
tags = ["conference"]
+++

### Abstract
Foundation models (FMs) trained with different objectives and data learn diverse representations, making some more effective than others for specific downstream tasks. Existing adaptation strategies, such as parameter-efficient fine-tuning, focus on individual models and do not exploit the complementary strengths across models. Probing methods offer a promising alternative by extracting information from frozen models, but current techniques do not scale well with large feature sets and often rely on dataset-specific hyperparameter tuning. We propose Combined backBones (ComBo), a simple and scalable probing-based adapter that effectively integrates features from multiple models and layers. ComBo compresses activations from layers of one or more FMs into compact token-wise representations and processes them with a lightweight transformer for task-specific prediction. Crucially, ComBo does not require dataset-specific tuning or backpropagation through the backbone models. However, not all models are equally relevant for all tasks. To address this, we introduce a mechanism that leverages ComBo's joint multi-backbone probing to efficiently evaluate each backbone's task-relevance, enabling both practical model comparison and improved performance through selective adaptation. On the 19 tasks of the VTAB-1k benchmark, ComBo outperforms previous probing methods, matches or surpasses more expensive alternatives, such as distillation-based model merging, and enables efficient probing of tuned models. Our results demonstrate that ComBo offers a practical and general-purpose framework for combining diverse representations from multiple FMs.

### Useful links
Paper: [https://doi.org/10.52202/085713-3009](https://doi.org/10.52202/085713-3009)

Preprint: [https://arxiv.org/abs/2512.01405](https://arxiv.org/abs/2512.01405)

### Bibtex

``` bibtex
@inproceedings{fantasticfeatures2025,
  author={Ramtoula, Benjamin and Lajoie, Pierre-Yves and Newman, Paul and De Martini, Daniele},
  title={Fantastic Features and Where to Find Them: A Probing Method to combine Features from Multiple Foundation Models},
  year={2025},
  booktitle={Advances in Neural Information Processing Systems 38 (NeurIPS)},
  pages={99925--99954},
  doi={10.52202/085713-3009},
  url={https://doi.org/10.52202/085713-3009},
}
```
