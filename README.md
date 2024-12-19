# TypeScript Type Error: Argument of type string[] is not assignable to parameter of type string
This example demonstrates a common TypeScript error that arises when passing an array of strings to a function expecting a single string.  The error message clearly indicates the type mismatch.  The solution involves either modifying the function signature to accept an array or iterating over the array to process individual strings.

## How to reproduce:
1. Save the code in `bug.ts`.
2. Compile using the TypeScript compiler (tsc).
3. Observe the compiler error.