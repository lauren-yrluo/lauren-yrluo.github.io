---
title: "Knowledge Compilation for Incremental and Checkable Stochastic Boolean Satisfiability"
collection: publications
permalink: /publication/2024-08-01-cheng-knowledge
excerpt: 'In this work, we extend knowledge compilation from model counting to stochastic Boolean satisfiability (SSAT) solving by generalizing the dec-DNNF representation to accommodate the SSAT quantifier structure and integrate it into SharpSSAT, a state-of-the-art SSAT solver. We further study proof generation from the compiled representation and extend CPOG, a certified model-counting toolchain, to generate proofs for certifying the results of SharpSSAT.'
date: 2024-08-01
venue: '2024 International Joint Conference on Artificial Intelligence (IJCAI)'
slidesurl: 'https://lauren-yrluo.github.io/files/KC_SSAT_slides.pdf'
paperurl: 'https://doi.org/10.24963/ijcai.2024/206'
authors: 'Che Cheng*, <b>Yun-Rong Luo*</b>, Jie-Hong Roland Jiang' 
citation: 'Che Cheng*, <b>Yun-Rong Luo*</b>, Jie-Hong Roland Jiang, "Knowledge Compilation for Incremental and Checkable Stochastic Boolean Satisfiability." 2024 International Joint Conference on Artificial Intelligence (IJCAI), 2024'
---

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