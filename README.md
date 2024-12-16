# JavaScript Null Handling Error

This repository demonstrates a common error in JavaScript where null values are not handled correctly and can lead to unexpected behavior or errors.

The `bug.js` file contains code that does not handle null values properly.  The `bugSolution.js` file shows how to correctly implement null handling using explicit checks for null values.

## Bug

The original code does not check for null values in the input parameters, leading to a potential error. 

## Solution

The solution involves explicitly checking for null values in the input parameters and returning an appropriate value, such as null, in case null is encountered. This prevents unexpected behavior and ensures that the function always returns a predictable result.
