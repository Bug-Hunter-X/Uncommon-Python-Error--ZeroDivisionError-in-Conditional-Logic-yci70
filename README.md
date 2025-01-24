# Uncommon Python Error: ZeroDivisionError in Conditional Logic

This repository demonstrates a simple Python function containing a less common error, the ZeroDivisionError that only occurs under a specific condition, namely, when the input is zero. The solution shows how to handle the error to prevent program crashes.

## Bug Description
The `function_with_uncommon_error` function can cause a `ZeroDivisionError` if the input value `x` is 0. This is because the code attempts to divide 1 by x, which results in division by zero.

## Solution
The solution involves using exception handling (try-except block) to gracefully handle the `ZeroDivisionError` and prevent the program from terminating abruptly. 
