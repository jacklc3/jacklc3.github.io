---
title: "Cambria: Resource Abstraction for Parametrized Algebraic Effects and Handlers"
date: 2026-07-02
author: ["Jack Liell-Cock", "Sam Staton"]
publication: "Preprint"
abstract: "The algebraic effects and handlers paradigm separates the concerns of the interface and implementation of computational effects in programming languages. We present Cambria, a language that extends this framework to the parametrized setting. Effect signatures may use abstract parameter types that are instantiated by the handler along with the operation implementations. Parameters abstract over resources, such as memory locations or thread IDs, permitting algebraic effects to encode dynamic allocation. They are first-class in the type system but erased at runtime, requiring no coercions or type-directed reduction.

We prove parametricity via a step-indexed logical relation, formalizing the abstraction guarantee provided by parametrized handlers. We also establish type safety and classify the annotations needed for completeness of the type inference algorithm. We demonstrate Cambria's practicality with a working implementation and provide examples including local state, Polya's urn, and concurrent thread management. The last is a parametrized effect whose abstract thread IDs are shared between concurrent computations, going beyond standard instances. Cambria is the first calculus with user-defined resource-allocating effects that guarantees, via parametricity, that client code cannot depend on how a handler represents its resources."
pdf: "paper.pdf"
code: "https://github.com/jacklc3/cambria"
playground: "https://cambria-lang.org/"
bib: "@misc{LiellCock2026,
  author = {Liell-Cock, Jack and Staton, Sam},
  title = {Cambria: Resource Abstraction for Parametrized Algebraic Effects and Handlers},
  year = {2026},
  howpublished = {Available on author's webpage.},
}"

---
