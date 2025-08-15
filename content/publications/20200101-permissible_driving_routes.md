+++
date = '2020-09-01T12:00:00Z'
draft = false
title = 'Keep off the Grass: Permissible Driving Routes from Radar with Weak Audio Supervision'
tags = ["conference", "radar", "driving_routes"]
+++

### Abstract
Reliable outdoor deployment of mobile robots requires the robust identification of permissible driving routes in a given environment. The performance of LiDAR and vision-based perception systems deteriorates significantly if certain environmental factors are present e.g. rain, fog, darkness. Perception systems based on Frequency-Modulated Continuous Wave scanning radar maintain full performance regardless of environmental conditions and with a longer range than alternative sensors. Learning to segment a radar scan based on driveability in a fully supervised manner is not feasible as labelling each radar scan on a bin-by-bin basis is both difficult and time-consuming to do by hand. We therefore weakly supervise the training of the radar-based classifier through an audio-based classifier that is able to predict the terrain type underneath the robot. By combining odometry, GPS and the terrain labels from the audio classifier, we are able to construct a terrain labelled trajectory of the robot in the environment which is then used to label the radar scans. Using a curriculum learning procedure, we then train a radar segmentation network to generalise beyond the initial labelling and to detect all permissible driving routes in the environment.

### Useful links
Paper: [IEEE](https://ieeexplore.ieee.org/document/9294415/)

### Bibtex
```bibtex
@INPROCEEDINGS{9294415,
  author={Williams, David and De Martini, Daniele and Gadd, Matthew and Marchegiani, Letizia and Newman, Paul},
  booktitle={2020 IEEE 23rd International Conference on Intelligent Transportation Systems (ITSC)}, 
  title={Keep off the Grass: Permissible Driving Routes from Radar with Weak Audio Supervision}, 
  year={2020},
  volume={},
  number={},
  pages={1-6},
  keywords={Radar;Training;Robots;Spectrogram;Labeling;Trajectory;Laser radar;radar;audio;terrain classification;weakly supervised learning},
  doi={10.1109/ITSC45102.2020.9294415}}
```
