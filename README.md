# Uninformative Error Message in MATLAB Function

This repository contains a MATLAB function that produces an uninformative error message when encountering an invalid input.  The provided solution demonstrates how to improve the error handling to provide more context and helpful information to the user.

## Bug

The `myFunction.m` file contains a function that checks for a negative input value. If the input is negative, it throws a generic error message: `'Input must be non-negative'`. This message lacks information regarding the function's name or the actual value of the input that caused the error, making it difficult to debug.

## Solution

The `myFunctionSolution.m` file provides an improved version of the function. The solution includes a more descriptive error message containing the function's name and the problematic input value.