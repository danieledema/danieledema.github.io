+++
date = '2025-11-01T00:00:00Z'
draft = false
title = "3D Foundation Model-Based Loop Closing for Decentralized Collaborative SLAM"
tags = ["journal", "localisation", "graph"]
# Only the publication month is known; the first day is used for chronological sorting.
+++

Also presented at ICRA 2026.

### Abstract
Decentralized Collaborative Simultaneous Localization And Mapping (C-SLAM) techniques often struggle to identify map overlaps due to significant viewpoint variations among robots. Motivated by recent advancements in 3D foundation models, which can register images despite large viewpoint differences, we propose a robust loop closing approach that leverages these models to establish inter-robot measurements. In contrast to resource-intensive methods requiring full 3D reconstruction within a centralized map, our approach integrates foundation models into existing SLAM pipelines, yielding scalable and robust multi-robot mapping. Our contributions include: (1) integrating 3D foundation models to reliably estimate relative poses from monocular image pairs within decentralized C-SLAM; (2) introducing robust outlier mitigation techniques critical to the use of these relative poses; and (3) developing specialized pose graph optimization formulations that efficiently resolve scale ambiguities. We evaluate our method against state-of-the-art approaches, demonstrating improvements in localization and mapping accuracy, alongside significant gains in computational and memory efficiency. These results highlight the potential of our approach for deployment in large-scale multi-robot scenarios.

### Useful links
Paper: [https://doi.org/10.1109/lra.2025.3609204](https://doi.org/10.1109/lra.2025.3609204)

Preprint: [https://arxiv.org/abs/2602.02430](https://arxiv.org/abs/2602.02430)

### Bibtex

``` bibtex
@article{foundationmodelloopclosing2025,
  author={Lajoie, Pierre-Yves and Ramtoula, Benjamin and De Martini, Daniele and Beltrame, Giovanni},
  title={3D Foundation Model-Based Loop Closing for Decentralized Collaborative SLAM},
  year={2025},
  journal={IEEE Robotics and Automation Letters},
  volume={10},
  number={11},
  pages={11188--11195},
  doi={10.1109/lra.2025.3609204},
  url={https://doi.org/10.1109/lra.2025.3609204},
}
```
