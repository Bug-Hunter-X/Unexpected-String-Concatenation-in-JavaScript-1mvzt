# JavaScript Loose Typing Bug

This repository demonstrates a common JavaScript error caused by the language's loose typing system. The function `foo` is intended to add two numbers, but due to the implicit type coercion, it performs string concatenation when one of the arguments is a string.

## Bug

The `bug.js` file contains the buggy code. Running it will show that the result is `12`, not `3` as one might expect.

## Solution

The `bugSolution.js` file provides a corrected version of the function.  Explicit type checking is used to ensure both arguments are numbers before performing the addition.

This example highlights the importance of careful type handling in JavaScript to avoid unexpected behavior.