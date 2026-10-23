+++
date = '2025-11-01T00:00:00Z'
draft = false
title = "Select2Plan: Training-Free ICL-Based Planning Through VQA and Memory Retrieval"
tags = ["journal", "infrastructure"]
# Only the publication month is known; the first day is used for chronological sorting.
+++

Also presented at ICRA 2026.

### Abstract
This study explores the potential of off-the-shelf Vision-Language Models (VLMs) for high-level robot planning in the context of autonomous navigation. Indeed, while most of existing learning-based approaches for path planning require extensive task-specific training/fine-tuning, we demonstrate how such training can be avoided for most practical cases. To do this, we introduce Select2Plan (S2P), a novel training-free framework for high-level robot planning which completely eliminates the need for fine-tuning or specialised training. By leveraging structured Visual Question-Answering (VQA) and In-Context Learning (ICL), our approach drastically reduces the need for data collection, requiring a fraction of the task-specific data typically used by trained models, or even relying only on online data. Our method facilitates the effective use of a generally trained VLM in a flexible and cost-efficient way, and does not require additional sensing except for a simple monocular camera. We demonstrate its adaptability across various scene types, context sources, and sensing setups. We evaluate our approach in two distinct scenarios: traditional First-Person View (FPV) and infrastructure-driven Third-Person View (TPV) navigation, demonstrating the flexibility and simplicity of our method. Our technique significantly enhances the navigational capabilities of a baseline VLM of approximately 50% in TPV scenario, and is comparable to trained models in the FPV one, with as few as 20 demonstrations.

### Useful links
Paper: [https://doi.org/10.1109/lra.2025.3606790](https://doi.org/10.1109/lra.2025.3606790)

Preprint: [https://arxiv.org/abs/2411.04006](https://arxiv.org/abs/2411.04006)

### Bibtex

``` bibtex
@article{select2plan2025,
  author={Buoso, Davide and Robinson, Luke and Averta, Giuseppe and Torr, Philip and Franzmeyer, Tim and De Martini, Daniele},
  title={Select2Plan: Training-Free ICL-Based Planning Through VQA and Memory Retrieval},
  year={2025},
  journal={IEEE Robotics and Automation Letters},
  volume={10},
  number={11},
  pages={11267--11274},
  doi={10.1109/lra.2025.3606790},
  url={https://doi.org/10.1109/lra.2025.3606790},
}
```
