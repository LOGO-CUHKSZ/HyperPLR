# HyperPLR: Hypergraph Generation through Projection, Learning, and Reconstruction

This repository contains the official implementation of our paper [HyperPLR: Hypergraph Generation through Projection, Learning, and Reconstruction](https://openreview.net/forum?id=TYnne6Pa35).

The dependency of the code is in ``requirement.txt``.

The framework can be found in ``main.ipynb``.

Some related method should be found in utils. (The algorithm ``GWC`` in the paper is implemented by function ``lazy_clique_edge_cover``)


## Dataset

- [Dataset](https://www.cs.cornell.edu/~arb/data/)

## Maximal cliques finding cost

- contact-high-school, 0.06284904479980469
- contact-primary-school, 0.8914539813995361
- email-Enron, 0.011591196060180664
- email-Eu, 3.432471990585327
- NDC-classes, 0.02602386474609375


## metrics

- hypergraph
  - density
  - average size
  - average degree
- projected graph
  - coefficient
  - modularity
- bipartite graph
  - modularity