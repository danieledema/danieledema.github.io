+++
date = 2020-09-01
draft = false
title = "Online Fall Detection Using Recurrent Neural Networks on Smart Wearable Devices"
tags = [journal, fall_detection, rnn, wearable]
+++

### Abstract
Unintentional falls can cause severe injuries and even death, especially if no immediate assistance is given. A fall detection system aims to detect a fall as soon as it occurs, therefore issuing an automatic assistance request. Wearable embedded sensors are emerging as the most viable solution for continuous monitoring since they are more effective, less intrusive and less expensive than other systems. Tailoring a deep learning method to the requirements of microcontrollers entails matching very stringent constraints in terms of both memory and computational power. In addition, datasets acquired with wearable devices are relatively scarce and not necessarily devised for supervised learning. In this work, we discuss the design of a software architecture based on recurrent neural networks which can be effective for fall detection while running entirely onboard a wearable device. The well-known and publicly-available SisFall dataset was adopted and extended with fine-grained temporal annotations to cope with the supervised training of recurrent neural networks. We then show that an appropriate process of architectural minimization together with accurate hyperparameters selection leads to a workable model which compares favorably with other detection techniques. The embedding of the resulting architecture has been validated using a state-of-art hardware device.

### Useful links
- [Paper on IEEE Xplore](https://ieeexplore.ieee.org/document/9209145/)

### Bibtex
```
@ARTICLE{9209145,
  author={Musci, Mirto and De Martini, Daniele and Blago, Nicola and Facchinetti, Tullio and Piastra, Marco},
  journal={IEEE Transactions on Emerging Topics in Computing}, 
  title={Online Fall Detection Using Recurrent Neural Networks on Smart Wearable Devices}, 
  year={2021},
  volume={9},
  number={3},
  pages={1276-1289},
  keywords={Biomedical monitoring;Feature extraction;Recurrent neural networks;Computer architecture;Batteries;Wearable sensors;C.3.d real-time and embedded systems;I.2.6.g machine learning;J.3.b health;I.2.9.j sensors;I.2.m.d wearable AI},
  doi={10.1109/TETC.2020.3027454}}
```
