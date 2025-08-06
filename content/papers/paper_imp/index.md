---
title: "Compositional Imprecise Probability"
date: 2025
author: ["Jack Liell-Cock", "Sam Staton"]
journal: "Proceedings of the Symposium on Principles of Programming Languages"

---

---

##### Download

+ [Pdf](paper.pdf)
+ [Talk](https://www.youtube.com/watch?v=ZjwLBLW7JdA)
+ [Arxiv](https://arxiv.org/abs/2405.09391)

---

##### Abstract

Imprecise probability is concerned with uncertainty about which probability distributions to use. It has applications in robust statistics and machine learning. We look at programming language models for imprecise probability. Our desiderata are that we would like our model to support all kinds of composition, categorical and monoidal; in other words, guided by dataflow diagrams. Another equivalent perspective is that we would like a model of synthetic probability in the sense of Markov categories. Imprecise probability can be modelled in various ways, with the leading monad-based approach using convex sets of probability distributions. This model is not fully compositional because the monad involved is not commutative, meaning it does not have a proper monoidal structure. In this work, we provide a new fully compositional account. The key idea is to name the non-deterministic choices. To manage the renamings and disjointness of names, we use graded monads. We show that the resulting compositional model is maximal and relate it with the earlier monadic approach, proving that we obtain tighter bounds on the uncertainty.

---

##### Citation

```BibTeX
@inproceedings{LiellCock2025,
  author = {Jack Liell-Cock and Sam Staton},
  title = {Compositional Imprecise Probability},
  year = {2025},
  booktitle = {Principles of Programming Languages},
  doi = {10.1145/3704890}
}
```
