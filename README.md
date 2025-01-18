# Type Error: Type 'string[]' is not assignable to type 'string'

This repository demonstrates a common type error in TypeScript where an array of strings is passed to a function expecting a single string. The error and its solution are explained below.

## Bug

The `greeter` function expects a single string argument, but the `user` variable is an array of strings. This mismatch causes a type error.

## Solution

The solution involves either modifying the `greeter` function to accept an array of strings or changing the `user` variable to a single string.  The solution provided modifies the `greeter` function to handle both single strings and arrays of strings.