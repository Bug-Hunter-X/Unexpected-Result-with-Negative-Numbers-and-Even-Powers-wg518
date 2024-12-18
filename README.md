# Julia Bug: Unexpected Result with Negative Numbers and Even Powers

This repository demonstrates an unusual behavior in Julia when calculating negative numbers raised to even powers. The issue arises from the way Julia handles exponentiation with negative bases and integer exponents. 

The `bug.jl` file contains a function that calculates the square of a number, handling negative values differently.  However, the result is not what one would intuitively expect. The `bugSolution.jl` shows a correction to address this issue.

## How to Reproduce

1. Clone this repository.
2. Open the `bug.jl` file in Julia.
3. Run the script.
4. Observe the unexpected result. 

## Solution

The solution involves handling the negative number before the exponentiation to ensure the expected mathematical result.