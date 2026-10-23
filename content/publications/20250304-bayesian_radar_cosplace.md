+++
date = '2025-03-04T00:00:00Z'
draft = false
title = "Bayesian Radar Cosplace: Directly Estimating Location Uncertainty in Radar Place Recognition"
tags = ["journal", "radar", "localisation", "uncertainty"]
+++

### Abstract
Trust and explainability in localisation systems can be greatly helped by estimating a calibrated uncertainty. In this work, we argue for the first time that for this, it is best to express uncertainty in the location estimate directly rather than indirectly in the ‘noisiness’ or ambiguity of the data sample. Therefore, in this work, through a robust classification‐based model, we not only identify the most probable place but also provide a measure of confidence or uncertainty associated with the prediction of the place itself—in contrast to existing approaches where uncertainty values are produced with the same dimension as the encoded feature. We specifically prove the utility of this new formulation on CosPlace , a state‐of‐the‐art Geolocalisation system. Uncertainty is learnt by transforming Cosplace into an uncertainty‐aware neural network. To validate the effectiveness of our approach, we conduct extensive experiments using the Oxford Radar RobotCar Dataset , where we find that the backbone features learnt in the uncertainty‐aware setting result in better place recognition performance than vanilla Cosplace . Furthermore, by using it as a score to reject putative localisation results, we show that our uncertainty is well‐calibrated to place recognition accuracy—more so than two existing systems in uncertainty‐aware radar place recognition.

### Useful links
Paper: [https://doi.org/10.1049/rsn2.70002](https://doi.org/10.1049/rsn2.70002)

### Bibtex

``` bibtex
@article{bayesianradarcosplace2025,
  author={Agarwal, Suyash and Yuan, Jianhao and Newman, Paul and De Martini, Daniele and Gadd, Matthew},
  title={Bayesian Radar Cosplace: Directly Estimating Location Uncertainty in Radar Place Recognition},
  year={2025},
  journal={IET Radar, Sonar \& Navigation},
  volume={19},
  number={1},
  doi={10.1049/rsn2.70002},
  url={https://doi.org/10.1049/rsn2.70002},
}
```
