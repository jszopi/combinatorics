[![license](https://img.shields.io/badge/license-CC_BY--SA-blue.svg?style=flat)](https://creativecommons.org/licenses/by-sa/4.0/)

## Implementations in programming languages

| Language             | Permutations       | Partial permutations  | Permutations with replacement | Multiset permutations                                                | Combinations          | Combinations with replacement          | 
| -------------------- | ------------------ | --------------------- | ----------------------------- | -------------------------------------------------------------------- | --------------------- | -------------------------------------- |
| Python (`itertools`) | `permutations (S)` | `permutations (S, k)` | `product(S, repeat=k)`        | inefficient: `set(permutations(S))` efficient: [ekg/multipermute][1] | `combinations (S, k)` | `combinations_with_replacement (S, k)` |

[1]: https://github.com/ekg/multipermute
