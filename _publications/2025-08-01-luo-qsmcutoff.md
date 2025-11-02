---
title: "QSM-Cutoff: Systematic Derivation of Quantified Cutoff Formulas for Distributed Protocols"
collection: publications
permalink: /publication/2025-08-01-luo-qsmcutoff
excerpt: 'We introduce [QSM-Cutoff](https://github.com/QSM-Cutoff/QSM-Cutoff), a new procedure that employs the quantified symmetric minimization algorithm from to systematically derive quantified formulas that precisely capture the onset of cutoff and saturation in distributed protocols.'
date: 2025-08-01
venue: 'Computer Aided Verification (CAV)'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-031-98682-6_14'
authors: '<b>Yun-Rong Luo</b>, Aman Goel, Karem Sakallah' 
citation: '<b>Yun-Rong Luo</b>, Aman Goel, Karem Sakallah, "QSM-Cutoff: Systematic Derivation of Quantified  Cutoff Formulas for Distributed Protocols.", 2025 International Conference on Computer Aided Verification (CAV), 2025'
---
### Paper and Slides 
[Paper URL](https://link.springer.com/chapter/10.1007/978-3-031-98682-6_14) 

### Software
[QSM-Cutoff](https://github.com/QSM-Cutoff/QSM-Cutoff)

### Abstract
We introduce QSM-Cutoff, a new procedure that employs the quantified symmetric minimization algorithm from [12] to systematically derive quantified formulas that precisely capture the onset of cutoff and saturation in distributed protocols. QSM-Cutoff performs symmetry-aware forward reachability to enumerate the reachable states of a finite protocol instance, and applies symmetry-preserving logic minimization to express these states as a minimum-cost finitely-quantified reachability formula. QSM-Cutoff repeats this finite analysis process to derive a sequence of reachability formulas  at increasing protocol sizes. This process terminates at size k when  is a unique solution to symmetric minimization that yields the exact set of reachable states when evaluated at size . We define  as the cutoff size and  as the cutoff formula. Empirically,  is shown to be a reachability invariant that encodes the reachable states for any protocol size.

QSM-Cutoff extends the finite analysis process in [12] by introducing two algorithmic enhancements: a depth-first search algorithm that enumerates the reachable states of a finite protocol by searching only for their symmetric quotient, and an extended quantification pattern inference algorithm that expresses explicit clause orbits of finite instances by logically equivalent quantified formulas. Empirical results demonstrate that, compared to the techniques used in [12], QSM-Cutoff is able to analyze a larger corpus of protocols, derive more compact quantified inductive invariants, and converge at smaller cutoffs. In contrast to previous scholarship, QSM-Cutoff offers a new angle for understanding the notions of cutoff and saturation of distributed protocols. In particular, it raises intriguing questions about the unexpected role of symmetric logic minimization in this much-researched area and opens new directions for further research.

### Citation
```
@InProceedings{10.1007/978-3-031-98682-6_14,
author="Luo, Yun-Rong
and Goel, Aman
and Sakallah, Karem",
editor="Piskac, Ruzica
and Rakamari{\'{c}}, Zvonimir",
title="QSM-Cutoff: Systematic Derivation of Quantified Cutoff Formulas for Distributed Protocols",
booktitle="Computer Aided Verification",
year="2025",
publisher="Springer Nature Switzerland",
address="Cham",
pages="263--286",
isbn="978-3-031-98682-6"
}
```