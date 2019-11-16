# SocialNetworkAnalysis
Social network analysis tool which finds matches of a given query graph in a social network.

DAF [[1](#reference)] is used to solve the subgraph matching problem.

## Environment
- The program is compiled on a machine with 64 bit CentOS Linux.

## Installation

Download the ``sna`` file.

## Usage example

Usage:

```sh
./sna -d [data graph file] -q [query graph file] -o [output file] -m [the number of matches want to retrieve]
```

Using example running:

```sh
git clone https://github.com/SNUCSE-CTA/SocialNetworkAnalysis.git
cd SocialNetworkAnalysis
chmod +x run.sh
./run.sh
```

run.sh:
```sh
./sna -d example.data -q example.query -o example.out -m 4
```

## Release History

* 0.1.0 [2019.11.16]
    * The first release

## License

Distributed under the Apache License 2.0. See ``LICENSE`` for more information.

## Reference

[1] M. Han, H. Kim, G. Gu, K. Park, and W.-S. Han, Efficient subgraph matching: Harmonizing dynamic programming, adaptive matching order, and failing set together. In: Proceedings of the ACM SIGMOD International Conference on Management of Data, 2019, pages 1429-1446
