# Generative Value Classifier

[![arXiv](https://img.shields.io/badge/arXiv-2610.22497-b31b1b.svg)](https://arxiv.org/abs/2610.22497)
[![Project Page](https://img.shields.io/badge/Project-Page-3f90da.svg)](https://alexanderswerdlow.github.io/gvc/)
![Code](https://img.shields.io/badge/Code-coming%20soon-lightgrey.svg)

[Alexander Swerdlow](https://aswerdlow.com/), [Perry Dong](https://pd-perry.github.io/), [Chelsea Finn](https://ai.stanford.edu/~cbfinn/)  
Stanford University

> [!NOTE]
> Code is coming soon (ETA: end of October)

<p align="center">
  <img src="docs/static/img/teaser.svg" width="720" alt="(a) A conventional critic maps a state and an action to Q(s,a), trained on a target y. (b) GVC combines a return-conditioned action model p(a|s,z) and a return prior p(z|s) to produce Q(s,a).">
</p>

We recast value learning as a generative classification problem: a return-conditioned policy scores each action under a set of returns, and these scores form an implicit Q-function.

## Citation

```bibtex
@misc{swerdlow2026gvc,
  title={Generative Value Classifier},
  author={Alexander Swerdlow and Perry Dong and Chelsea Finn},
  year={2026},
  eprint={2610.22497},
  archivePrefix={arXiv},
  primaryClass={cs.LG},
  url={https://arxiv.org/abs/2610.22497}
}
```
