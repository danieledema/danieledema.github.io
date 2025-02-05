+++
date = '2023-11-26T12:07:04Z'
draft = false
title = 'What You See Is What You Get: Experience Ranking with Deep Neural Dataset-to-Dataset Similarity for Topological Localisation'
tags = ["conference", "representation", "localisation"]
+++

### Abstract
Recalling the most relevant visual memories for localisation or understanding a priori the likely outcome of localisation effort against a particular visual memory is useful for efficient and robust visual navigation.
Solutions to this problem should be divorced from performance appraisal against ground truth – as this is not available at run-time – and should ideally be based on generalisable environmental observations.
For this, we propose applying the recently developed Visual DNA as a highly scalable tool for comparing datasets of images – in this work, sequences of past (map) and live experiences.
In the case of localisation, important dataset differences impacting performance are modes of appearance change, including weather, lighting, and season.
Specifically, for any deep architecture which is used for place recognition by matching feature volumes at a particular layer, we use distribution measures to compare neuron-wise activation statistics between live images and multiple previously recorded past experiences, with a potentially large seasonal (winter/summer) or time of day (day/night) shift.
We find that differences in these statistics correlate to performance when localising using a past experience with the same appearance gap.
We validate our approach over the Nordland cross-season dataset as well as data from Oxford’s University Parks with lighting and mild seasonal change, showing excellent ability of our system to rank actual localisation performance across candidate experiences

### Useful links
Paper: [https://link.springer.com/chapter/10.1007/978-3-031-63596-0_53](https://link.springer.com/chapter/10.1007/978-3-031-63596-0_53)

### Bibtex 

``` bibtex
@INPROCEEDINGS{gadd2023,
author="Gadd, Matthew and Ramtoula, Benjamin and De Martini, Daniele and Newman, Paul",
editor="Ang Jr, Marcelo H. and Khatib, Oussama",
title="What You See Is What You Get: Experience Ranking with Deep Neural Dataset-to-Dataset Similarity for Topological Localisation",
booktitle="Experimental Robotics",
year="2024",
publisher="Springer Nature Switzerland",
address="Cham",
pages="595--607",
isbn="978-3-031-63596-0"
}
```
