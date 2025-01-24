# Stack Overflow in Recursive Factorial Function

This repository demonstrates a common error in recursive functions: stack overflow. The `foo` function calculates the factorial of a number recursively.  For large inputs, this leads to excessive function calls, exceeding the call stack limit.

The solution provided demonstrates an iterative approach to calculating the factorial, avoiding the stack overflow issue.

## Bug

The `bug.hack` file contains the buggy recursive factorial function. Running it with a sufficiently large input (e.g., 1000) will cause a stack overflow.

## Solution

The `bugSolution.hack` file provides a corrected version using an iterative approach, which avoids stack overflow issues.

## How to Run

1.  Clone this repository.
2.  You will need to have a Hack compiler/interpreter to run this code.  Instructions will vary depending on your environment. 