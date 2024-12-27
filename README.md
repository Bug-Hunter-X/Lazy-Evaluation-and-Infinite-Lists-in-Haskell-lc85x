# Haskell Lazy Evaluation Bug
This repository demonstrates a subtle bug in Haskell code that arises from the interaction of lazy evaluation, infinite lists, and the `sum` function.

The `bug.hs` file contains the buggy code. The `bugSolution.hs` file shows how to resolve the issue by forcing evaluation to a finite list before applying the `sum` function.

This bug highlights the importance of understanding how Haskell's lazy evaluation mechanism works and how to avoid potential pitfalls when working with infinite data structures.