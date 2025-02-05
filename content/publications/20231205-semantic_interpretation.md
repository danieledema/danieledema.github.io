+++
date = '2023-12-05T12:07:04Z'
draft = false
title = 'Semantic Interpretation and Validation of Graph Attention-Based Explanations for GNN Models'
tags = ["conference", "graph", "explainability", "registration", "pointcloud"]
+++

### Abstract
In this work, we propose a methodology for investigating the use of semantic attention to enhance the explainability of Graph Neural Network (GNN)-based models.
Graph Deep Learning (GDL) has emerged as a promising field for tasks like scene interpretation, leveraging flexible graph structures to concisely describe complex features and relationships.
As traditional explainability methods used in eXplainable AI (XAI) cannot be directly applied to such structures, graph-specific approaches are introduced.
Attention has been previously employed to estimate the importance of input features in GDL, however, the fidelity of this method in generating accurate and consistent explanations has been questioned.
To evaluate the validity of using attention weights as feature importance indicators, we introduce semantically-informed perturbations and correlate predicted attention weights with the accuracy of the model.
Our work extends existing attention-based graph explainability methods by analysing the divergence in the attention distributions in relation to semantically sorted feature sets and the behaviour of a GNN model, efficiently estimating feature importance.
We apply our methodology on a lidar pointcloud estimation model successfully identifying key semantic classes that contribute to enhanced performance, effectively generating reliable post-hoc semantic explanations

### Useful links
Paper: [https://ieeexplore.ieee.org/abstract/document/10406370](https://ieeexplore.ieee.org/abstract/document/10406370)

### Bibtex 

``` bibtex
@INPROCEEDINGS{panagiotaki2023,
  author={Panagiotaki, Efimia and De Martini, Daniele and Kunze, Lars},
  booktitle={2023 21st International Conference on Advanced Robotics (ICAR)}, 
  title={Semantic Interpretation and Validation of Graph Attention-Based Explanations for GNN Models}, 
  year={2023},
  volume={},
  number={},
  pages={375-380},
  keywords={Correlation;Semantics;Predictive models;Graph neural networks;Reliability;Task analysis;Robots;Attention;eXplanable AI;graph neural networks;pose estimation},
  doi={10.1109/ICAR58858.2023.10406370}}
```
