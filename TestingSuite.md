The following is several tests with varying Character Sets and Permutation String Lengths. Note that, at first, the number of recursive calls is a bit larger than the number of permutations,
but as the Character Sets and the Permutation String Lengths get longer, the rate at which the number of recursive function calls increases becomes exponentially slower.
These outputs can be reproduced by using these inputs in the project contained within the "FindStringPermutations-BenchmarkVersion.zip" file.

Character Set: {A, B, C}
Length of Permutation Strings: 3
Number of Permutations: 10
Recursive function calls: 16
Largest Call-Stack Size: 4

Character Set: {Z, Y, X}
Length of Permutation Strings: 3
Number of Permutations: 10
Recursive function calls: 16
Largest Call-Stack Size: 4

Character Set: {A, B, C}
Length of Permutation Strings: 5
Number of Permutations: 21
Recursive function calls: 28
Largest Call-Stack Size: 6

Character Set: {A, B, C}
Length of Permutation Strings: 100
Number of Permutations: 5151
Recursive function calls: 598
Largest Call-Stack Size: 101

Character Set: {A, B, C, D}
Length of Permutation Strings: 5
Number of Permutations: 56
Recursive function calls: 45
Largest Call-Stack Size: 6

Character Set: {A, B, C, D}
Length of Permutation Strings: 100
Number of Permutations: 176851
Recursive function calls: 995
Largest Call-Stack Size: 101

Character Set: {Z, Y, X, 7, 3, 2}
Length of Permutation Strings: 3
Number of Permutations: 56
Recursive function calls: 49
Largest Call-Stack Size: 4

Character Set: {Z, Y, X, 7, 3, 2}
Length of Permutation Strings: 10
Number of Permutations: 3003
Recursive function calls: 196
Largest Call-Stack Size: 11

Character Set: {Z, Y, X, 7, 3, 2}
Length of Permutation Strings: 100
Number of Permutations: 96560646
Recursive function calls: 2086
Largest Call-Stack Size: 101
