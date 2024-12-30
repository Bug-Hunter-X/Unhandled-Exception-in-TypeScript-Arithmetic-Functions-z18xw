# Unhandled Exception in TypeScript Arithmetic Functions

This repository demonstrates a common error in TypeScript: failing to properly handle potential runtime errors.  The example involves basic arithmetic functions, where a division by zero can cause an unhandled exception.

The `bug.ts` file showcases the problematic code, while `bugSolution.ts` provides a corrected version with better error handling.

## Bug Description

The `divide` function in `bug.ts` lacks appropriate error handling. When the divisor is zero, an exception is thrown, but it isn't caught, leading to program termination.

## Solution

The `bugSolution.ts` file demonstrates how to use `try...catch` blocks to gracefully handle the exception, preventing the program from crashing.  A more user-friendly message is also provided.