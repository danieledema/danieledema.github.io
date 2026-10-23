+++
date = '2025-10-08T00:00:00Z'
draft = false
title = "Introspection in Learned Semantic Scene Graph Localisation"
tags = ["workshop", "localisation", "graph"]
+++

### Abstract
This work investigates how semantics influence localisation performance and robustness in a learned self-supervised, contrastive semantic localisation framework. After training a localisation network on both original and perturbed maps, we conduct a thorough post-hoc introspection analysis to probe whether the model filters environmental noise and prioritises distinctive landmarks over routine clutter. We validate various interpretability methods and present a comparative reliability analysis. Integrated gradients and Attention Weights consistently emerge as the most reliable probes of learned behaviour. A semantic class ablation further reveals an implicit weighting in which frequent objects are often down-weighted. Overall, the results indicate that the model learns noise-robust, semantically salient relations about place definition, thereby enabling explainable registration under challenging visual and structural variations.

### Useful links
Preprint: [https://arxiv.org/abs/2510.07053](https://arxiv.org/abs/2510.07053)

### Bibtex

``` bibtex
@inproceedings{scenegraphintrospection2025,
  author={Manshika Charvi Bissessur and Efimia Panagiotaki and Daniele De Martini},
  title={Introspection in Learned Semantic Scene Graph Localisation},
  year={2025},
  booktitle={IROS Workshop on Fully Autonomy Emerges from Cognition (FAST)},
  url={https://arxiv.org/abs/2510.07053},
}
```
