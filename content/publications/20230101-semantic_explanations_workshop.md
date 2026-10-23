+++
date = '2023-01-01T00:00:00Z'
draft = false
title = "Towards Semantic Interpretation and Validation of Graph Attention-based Explanations"
tags = ["workshop", "graph"]
# Only the publication year is known; the first day is used for chronological sorting.
+++

### Abstract
In this work, we investigate the use of semantic attention to explain the performance of a Graph Neural Network (GNN)-based pose estimation model. To validate our approach, we apply semantically-informed perturbations to the input data and correlate the predicted feature importance weights with the accuracy of the model.

Graph Deep Learning (GDL) is an emerging field of machine learning for tasks like scene interpretation, as it exploits flexible graph structures to describe complex features and relationships in a very concise format. However, due to the unconventional structure of the graphs, traditional explainability methods used in eXplainable AI (XAI) require further adaptation and thus, graph-specific methods are introduced.

Attention is a powerful tool, introduced to estimate the importance of input features in deep learning models. It has been previously used to provide feature-based explanations on the predictions of GNN models. In our proposed work, we exploit graph attention to identify key semantic classes for lidar pointcloud pose estimation. We extend the current attention-based graph explainability methods by investigating the use of attention weights as importance indicators of semantically sorted feature sets by analysing the correlation between attention weights distribution and model accuracy. Our method has shown promising results for post-hoc semantic explanation of graph-based pose estimation.

### Useful links
Paper: [https://nms.kcl.ac.uk/icra2023.explainablerobotics/papers/xro-panagiotaki.pdf](https://nms.kcl.ac.uk/icra2023.explainablerobotics/papers/xro-panagiotaki.pdf)

### Bibtex

``` bibtex
@inproceedings{semanticexplanationsworkshop2023,
  author={Panagiotaki, E. and De Martini, D. and Kunze, L.},
  title={Towards Semantic Interpretation and Validation of Graph Attention-based Explanations},
  year={2023},
  booktitle={ICRA Workshop on Explainable Robotics},
  url={https://nms.kcl.ac.uk/icra2023.explainablerobotics/papers/xro-panagiotaki.pdf},
}
```
