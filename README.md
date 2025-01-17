# ZeroDivisionError in Python Function

This repository demonstrates a simple Python function that can trigger a `ZeroDivisionError`. This error occurs when attempting to divide by zero, a common but easily overlooked issue in programming.

The `bug.py` file contains the function with the error, while `bugSolution.py` provides a corrected version with robust error handling. 

## How to Reproduce

1. Clone this repository.
2. Run `bug.py` with input 0.  This will cause the `ZeroDivisionError`.
3. Run `bug.py` with input other than 0, to show the non-erroneous behavior.
4. Run `bugSolution.py` to see how the error is handled gracefully.

## Solution

The solution involves adding error handling using a `try-except` block to catch the `ZeroDivisionError` and return an appropriate value (or handle the exception as needed) rather than letting the program crash. 