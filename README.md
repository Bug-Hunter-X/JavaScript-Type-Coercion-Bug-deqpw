# JavaScript Type Coercion Bug

This repository demonstrates a common yet often overlooked issue in JavaScript: type coercion during arithmetic operations.  The `bug.js` file contains a function that inadvertently concatenates a number and string due to JavaScript's loose typing.  The `bugSolution.js` file provides a solution showing how to enforce type checking to prevent this unexpected behavior.

## How to Reproduce

1. Clone the repository.
2. Run `bug.js`. Observe that the output is "55" instead of the expected numerical sum of 10.
3. Run `bugSolution.js`. Observe the corrected output of 10.

## Learning Points

This example highlights the importance of understanding JavaScript's automatic type coercion.  In many cases, this behavior can lead to unexpected results.  Explicit type checking is crucial for avoiding such errors and ensuring the reliability and predictability of your code.