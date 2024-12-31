# Type 'string[]' is not assignable to type 'string'

This repository demonstrates a common TypeScript error: assigning an array of strings to a parameter expecting a single string.

## Bug

The `greeter` function expects a single string as input. However, the code attempts to pass an array of strings. TypeScript correctly identifies this type mismatch and throws an error.

## Solution

The solution involves either modifying the `greeter` function to accept an array of strings or modifying the input to provide a single string.