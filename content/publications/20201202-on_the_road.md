+++
date = '2020-12-02T00:00:00Z'
draft = false
title = "On the Road: Route Proposal from Radar Self-Supervised by Fuzzy LiDAR Traversability"
tags = ["journal", "radar"]
+++

### Abstract
This is motivated by a requirement for robust, autonomy-enabling scene understanding in unknown environments. In the method proposed in this paper, discriminative machine-learning approaches are applied to infer traversability and predict routes from Frequency-Modulated Contunuous-Wave (FMCV) radar frames. Firstly, using geometric features extracted from LiDAR point clouds as inputs to a fuzzy-logic rule set, traversability pseudo-labels are assigned to radar frames from which weak supervision is applied to learn traversability from radar. Secondly, routes through the scanned environment can be predicted after they are learned from the odometry traces arising from traversals demonstrated by the autonomous vehicle (AV). In conjunction, therefore, a model pretrained for traversability prediction is used to enhance the performance of the route proposal architecture. Experiments are conducted on the most extensive radar-focused urban autonomy dataset available to the community. Our key finding is that joint learning of traversability and demonstrated routes lends itself best to a model which understands where the vehicle should feasibly drive. We show that the traversability characteristics can be recovered satisfactorily, so that this recovered representation can be used in optimal path planning, and that an end-to-end formulation including both traversability feature extraction and routes learned by expert demonstration recovers smooth, drivable paths that are comprehensive in their coverage of the underlying road network. We conclude that the proposed system will find use in enabling mapless vehicle autonomy in extreme environments.

### Useful links
Paper: [https://doi.org/10.3390/ai1040033](https://doi.org/10.3390/ai1040033)

### Bibtex

``` bibtex
@article{ontheroad2020,
  author={Broome, Michael and Gadd, Matthew and De Martini, Daniele and Newman, Paul},
  title={On the Road: Route Proposal from Radar Self-Supervised by Fuzzy LiDAR Traversability},
  year={2020},
  journal={AI},
  volume={1},
  number={4},
  pages={558--585},
  doi={10.3390/ai1040033},
  url={https://doi.org/10.3390/ai1040033},
}
```
