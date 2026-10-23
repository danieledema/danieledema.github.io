+++
date = '2023-06-01T00:00:00Z'
draft = false
title = "Visual DNA: Representing and Comparing Images Using Distributions of Neuron Activations"
tags = ["conference", "dataset"]
# Only the publication month is known; the first day is used for chronological sorting.
+++

Also presented at the UK AI Research Symposium 2025 and the DataCV Workshop at ICCV 2025, where it received the Best Paper Award.

### Abstract
Selecting appropriate datasets is critical in modern computer vision. However, no general-purpose tools exist to evaluate the extent to which two datasets differ. For this, we propose representing images - and by extension datasets - using Distributions of Neuron Activations (DNAs). DNAs fit distributions, such as histograms or Gaussians, to activations of neurons in a pre-trained feature extractor through which we pass the image(s) to represent. This extractor is frozen for all datasets, and we rely on its generally expressive power in feature space. By comparing two DNAs, we can evaluate the extent to which two datasets differ with granular control over the comparison attributes of interest, providing the ability to customise the way distances are measured to suit the requirements of the task at hand. Furthermore, DNAs are compact, representing datasets of any size with less than 15 megabytes. We demonstrate the value of DNAs by evaluating their applicability on several tasks, including conditional dataset comparison, synthetic image evaluation, and transfer learning, and across diverse datasets, ranging from synthetic cat images to celebrity faces and urban driving scenes.

### Useful links
Paper: [https://doi.org/10.1109/cvpr52729.2023.01069](https://doi.org/10.1109/cvpr52729.2023.01069)

Preprint: [https://arxiv.org/abs/2304.10036](https://arxiv.org/abs/2304.10036)

### Bibtex

``` bibtex
@inproceedings{visualdna2023,
  author={Ramtoula, Benjamin and Gadd, Matthew and Newman, Paul and De Martini, Daniele},
  title={Visual DNA: Representing and Comparing Images Using Distributions of Neuron Activations},
  year={2023},
  booktitle={2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
  pages={11113--11123},
  doi={10.1109/cvpr52729.2023.01069},
  url={https://doi.org/10.1109/cvpr52729.2023.01069},
}
```
