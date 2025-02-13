# RecursionError in Factorial Function

This repository demonstrates a common error in Python: a RecursionError caused by a missing base case in a recursive function.

The `bug.py` file contains the buggy factorial function. The `bugSolution.py` file shows the corrected version.

## Bug

The factorial function fails to handle negative input values, resulting in infinite recursion and a `RecursionError`.

## Solution

The solution adds a check for negative input values, returning an error message or handling them appropriately.