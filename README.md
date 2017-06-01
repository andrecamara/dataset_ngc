# dataset_ngc
Datasets of the Paper "Centrality-based Group Profiling: A Comparative Study in Co-Authorship Networks"

This dataset consists of a co-authorship network extracted from data collected in arXiv (https://arxiv.org/), in the field of Artificial Intelligence, published between 2012 and 2014. In the constructed network, each node represents an author and two nodes are connected if they have co-authored at least one paper. The resulting network contained 1850 authors with 2560 relationships.

Network related measures of the initial arXiv co-occurrence network and after filter application


|Measure | Original | Filtered |
|---|---:|---:|
|Number of Authors | 1850    | 372  |
|Number of Links   | 2560    | 654   |
|Link Density      | 0.001   | 0.009 |
|Average Link      | 2.768   | 3.516 |
|Diameter          | 19      | 19    |
|Number of Groups  | 439     | 10   |
