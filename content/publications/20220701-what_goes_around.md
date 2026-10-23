+++
date = '2022-07-01T00:00:00Z'
draft = false
title = "What Goes Around: Leveraging a Constant-Curvature Motion Constraint in Radar Odometry"
tags = ["journal", "radar"]
# Only the publication month is known; the first day is used for chronological sorting.
+++

### Abstract
This paper presents a method that leverages vehicle motion constraints to refine data associations in a point-based radar odometry system. By using the strong prior on how a non-holonomic robot is constrained to move smoothly through its environment, we develop the necessary framework to estimate ego-motion from a single landmark association rather than considering all of these correspondences at once. This allows for informed outlier detection of poor matches that are a dominant source of pose estimate error. By refining the subset of matched landmarks, we see an absolute decrease of 2.15% (from 4.68% to 2.53%) in translational error, approximately halving the error in odometry (reducing by 45.94%) than when using the full set of correspondences. This contribution is relevant to other point-based odometry implementations that rely on a range sensor and provides a lightweight and interpretable means of incorporating vehicle dynamics for ego-motion estimation.

### Useful links
Paper: [https://doi.org/10.1109/lra.2022.3186757](https://doi.org/10.1109/lra.2022.3186757)

Preprint: [https://arxiv.org/abs/2206.10517](https://arxiv.org/abs/2206.10517)

### Bibtex

``` bibtex
@article{whatgoesaround2022,
  author={Aldera, Roberto and Gadd, Matthew and De Martini, Daniele and Newman, Paul},
  title={What Goes Around: Leveraging a Constant-Curvature Motion Constraint in Radar Odometry},
  year={2022},
  journal={IEEE Robotics and Automation Letters},
  volume={7},
  number={3},
  pages={7865--7872},
  doi={10.1109/lra.2022.3186757},
  url={https://doi.org/10.1109/lra.2022.3186757},
}
```
