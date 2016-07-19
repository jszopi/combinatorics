[![license](https://img.shields.io/badge/license-CC_BY--SA-blue.svg?style=flat)](https://creativecommons.org/licenses/by-sa/4.0/)
[![Build Status](https://travis-ci.org/jszopi/combinatorics.svg?branch=master)](https://travis-ci.org/jszopi/combinatorics)

The highlight of this repo is the LaTeX document, which outlines the most important concepts in combinatorics.
It also includes Polish names for the discussed operations and attempts to make sense of such dissimilar terminology.
The latest release can be downloaded [here](https://github.com/jszopi/combinatorics/releases/download/v0.2/essential_combinatorics.pdf).

Another useful resource should be the table in the next section.

## Implementations in programming languages

| Language             | Permutations       | Partial permutations  | Permutations with replacement | Multiset permutations                                                | Combinations          | Combinations with replacement          | 
| -------------------- | ------------------ | --------------------- | ----------------------------- | -------------------------------------------------------------------- | --------------------- | -------------------------------------- |
| Python (`itertools`) | `permutations (S)` | `permutations (S, k)` | `product(S, repeat=k)`        | inefficient: `set(permutations(S))` efficient: [ekg/multipermute][1] | `combinations (S, k)` | `combinations_with_replacement (S, k)` |

[1]: https://github.com/ekg/multipermute
