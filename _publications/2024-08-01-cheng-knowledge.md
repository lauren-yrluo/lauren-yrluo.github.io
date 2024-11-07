---
title: "Knowledge Compilation for Incremental and Checkable Stochastic Boolean Satisfiability"
collection: publications
permalink: /publication/2024-08-01-cheng-knowledge
excerpt: 'In this work, we generalize the dec-DNNF representation to stochastic Boolean satisfiability (SSAT). We integrate knowledge compilation into [SharpSSAT](https://github.com/NTU-ALComLab/SharpSSAT)[(AAAI23 paper)](https://ojs.aaai.org/index.php/AAAI/article/view/25509), a state-of-the-art SSAT solver. We extend [CPOG](https://github.com/rebryant/cpog)[(SAT23 paper)](https://doi.org/10.4230/LIPIcs.SAT.2023.6), a certified model-counting toolchain, and develop the [cert-SSAT](https://github.com/NTU-ALComLab/cert-SSAT) toolchain for certifying the results of SharpSSAT.'
date: 2024-08-01
venue: 'International Joint Conference on Artificial Intelligence (IJCAI)'
slidesurl: 'https://lauren-yrluo.github.io/files/KC_SSAT_slides.pdf'
paperurl: 'https://doi.org/10.24963/ijcai.2024/206'
authors: 'Che Cheng*, <b>Yun-Rong Luo*</b>, Jie-Hong Roland Jiang' 
citation: 'Che Cheng*, <b>Yun-Rong Luo*</b>, Jie-Hong Roland Jiang, "Knowledge Compilation for Incremental and Checkable Stochastic Boolean Satisfiability." 2024 International Joint Conference on Artificial Intelligence (IJCAI), 2024'
---
### Paper and Slides 
[Paper URL](https://doi.org/10.24963/ijcai.2024/206) 
[Download Slides](https://lauren-yrluo.github.io/files/KC_SSAT_slides.pdf)

### Software
[SharpSSAT](https://github.com/NTU-ALComLab/SharpSSAT)
[cert-SSAT](https://github.com/NTU-ALComLab/cert-SSAT)

### Abstract
Knowledge compilation has proven effective in (weighted) model counting, uniquely supporting incrementality and checkability. For incrementality, compiling an input formula once suffices to answer multiple queries, thus reducing the total solving effort. For checkability, the compiled formula is amenable to producing machine-checkable proofs for verification, thus strengthening the solver’s reliability. In this work, we extend knowledge compilation from model counting to stochastic Boolean satisfiability (SSAT) solving by generalizing the dec-DNNF representation to accommodate the SSAT quantifier structure and integrate it into SharpSSAT, a state-of-the-art SSAT solver. We further study proof generation from the compiled representation and extend CPOG, a certified model-counting toolchain, to generate proofs for certifying the results of SharpSSAT. Experimental results show the benefits of the proposed knowledge compilation approach for SSAT in sharing computation efforts for multiple queries and producing checkable dec-DNNF logs with negligible overhead.

### Citation
```
@inproceedings{cheng_knowledge_2024,
  title     = {Knowledge Compilation for Incremental and Checkable Stochastic Boolean Satisfiability},
  author    = {Cheng, Che and Luo, Yun-Rong and Jiang, Jie-Hong R.},
  booktitle = {Proceedings of the Thirty-Third International Joint Conference on
               Artificial Intelligence, {IJCAI-24}},
  publisher = {International Joint Conferences on Artificial Intelligence Organization},
  editor    = {Kate Larson},
  pages     = {1862--1872},
  year      = {2024},
  month     = {8},
  note      = {Main Track},
  doi       = {10.24963/ijcai.2024/206},
  url       = {https://doi.org/10.24963/ijcai.2024/206},
}
```