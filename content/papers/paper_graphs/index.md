---
title: "Let a Thousand Flowers Bloom: An Algebraic Representation for Edge Graphs"
year: 2024
author: ["Jack Liell-Cock", "Tom Schrijvers"]
publication: "The Art, Science, and Engineering of Programming"
doi: "10.22152/programming-journal.org/2024/8/9"
pdf: "paper.pdf"
arxiv: "https://arxiv.org/abs/2403.02273"
abstract: "Context: Edge graphs are graphs whose edges are labelled with identifiers, and nodes can have multiple edges between them. They are used to model a wide range of systems, including networks with distances or degrees of connection and complex relational data.

Inquiry: Unfortunately, the homogeneity of this graph structure prevents an effective representation in (functional) programs. Either their interface is riddled with partial functions, or the representations are computationally inefficient to process.

Approach: We present a novel data type for edge graphs, based on total and recursive definitions, that prevents usage errors from partial APIs and promotes structurally recursive computations. We follow an algebraic approach and provide a set of primitive constructors and combinators, along with equational laws that identify semantically equivalent constructions.

Knowledge: This algebra translates directly into an implementation using algebraic data types, and its homomorphisms give rise to functions for manipulating and transforming these edge graphs.

Grounding: We exploit the fact that many common graph algorithms are such homomorphisms to implement them in our framework.

Importance: In giving a theoretical grounding for the edge graph data type, we can formalise properties such as soundness and completeness of the representation while also minimising usage errors and maximising re-usability."
bib: "@article{LiellCock2024,
  title = {Let a Thousand Flowers Bloom: An Algebraic Representation for Edge Graphs},
  author = {Jack Liell-Cock and Tom Schrijvers},
  year = {2024},
  journal = {The Art, Science, and Engineering of Programming},
  number = {3},
  pages = {9:1-9:28},
  issn = {2473-7321},
  doi = {10.22152/programming-journal.org/2024/8/9}
}"

---
