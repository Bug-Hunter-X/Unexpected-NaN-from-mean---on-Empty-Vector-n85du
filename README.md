# R Bug: Handling Empty Vectors in mean() Calculation

This repository demonstrates a common issue in R when calculating the mean of an empty numeric vector. The `mean()` function, when encountering an empty vector, returns `NaN` (Not a Number) and issues a warning. This behavior can be problematic if not handled appropriately.

The `bug.R` file contains the buggy code, while `bugSolution.R` provides a solution to gracefully handle this scenario.

## How to reproduce
1. Clone this repository.
2. Open `bug.R`.
3. Run the code. You'll see a warning message and `NaN` printed to the console.

## Solution
The `bugSolution.R` file shows how to check for empty vectors before applying the `mean()` function, preventing the error.