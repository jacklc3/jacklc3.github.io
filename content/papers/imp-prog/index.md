---
title: "Imprecise Probabilistic Programming, Precisely (Functional Pearl)"
date: 2026-07-01
author: ["Jack Liell-Cock", "Sam Staton"]
publication: "International Conference on Functional Programming"
doi: "10.1145/3828698"
abstract: "Imprecise probability generalizes standard probability theory by replacing a single distribution with a convex set of possible distributions. We show that this generalization requires no change to the standard BDD compilation and weighted model counting pipeline used by discrete probabilistic languages. An imprecise coin flip is simply a BDD variable whose weight is left free rather than fixed. We introduce Imp, a Haskell-embedded DSL for imprecise probabilistic programming. A graded monad, indexed by finite sets of named sources of epistemic uncertainty, restores the commutativity that the standard convex powerset monad lacks, and GHC's type system enforces this at compile time. Weighted model counting is parametric in the semiring, so the same compiled BDD supports exact, differentiable, and interval-bounded inference."
pdf: "pearl.pdf"
arxiv: "https://arxiv.org/abs/2607.20801"
bib: "@inproceedings{LiellCock2026,
  author = {Liell-Cock, Jack and Staton, Sam},
  title = {Imprecise Probabilistic Programming, Precisely (Functional Pearl)},
  year = {2026},
  booktitle = {Proc. ICFP~2026},
  doi = {10.1145/3828698}
}"

---
