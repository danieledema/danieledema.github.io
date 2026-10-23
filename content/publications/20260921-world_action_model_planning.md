+++
date = '2026-09-21T00:00:00Z'
draft = false
title = "Beyond Visual Quality: A Study of Test-Time Planning with World Action Models"
tags = ["preprint"]
+++

### Abstract
World action models generate actions together with visual predictions of their consequences. These paired outputs create the potential for planning by sampling multiple actions from one state, comparing their imagined outcomes, and choosing the action with the most promising predicted outcome. However, how to use imagined futures to guide action selection remains unclear. We examine this planning potential empirically. First, we estimate an oracle upper bound on selection by choosing the sampled candidate whose realised outcome is best. In a controlled same-state analysis, this choice raises success from 68.9% under uniform random selection to 79.2%. We then test selectors based on visual quality, physical consistency, and task progression as controlled interventions. Some tested selectors yield higher observed success, but the gains are uneven and the matched selectors leave much of the measured opportunity unrecovered. To investigate this gap, we examine whether sampled actions lead to different outcomes, whether these differences are visible in the predictions, and whether a score recognises them. Counterfactual branching from the same states shows that selection opportunity is concentrated in relatively few decisions in the initial candidate sets. Action spread and outcome coverage need not increase together. In a further evaluation across trajectory phases with complete action execution, the tested scores again recover little of the available improvement despite a small gain from learned value. These findings distinguish producing consequential action choices from recognising them in generated futures, motivating the evaluation of WAM predictions through their usefulness for decisions rather than visual quality alone.

### Useful links
Paper: [https://arxiv.org/abs/2609.24745](https://arxiv.org/abs/2609.24745)

### Bibtex

``` bibtex
@misc{worldactionmodelplanning2026,
  author={Jianhao Yuan and Yu Yuan and Benjamin Ramtoula and Lukas Vierling and Paul Newman and Lars Kunze and Philip Torr and Daniele De Martini},
  title={Beyond Visual Quality: A Study of Test-Time Planning with World Action Models},
  year={2026},
  eprint={2609.24745},
  archivePrefix={arXiv},
  url={https://arxiv.org/abs/2609.24745},
}
```
