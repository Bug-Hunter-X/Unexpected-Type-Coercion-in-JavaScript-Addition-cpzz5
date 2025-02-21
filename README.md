# Unexpected Type Coercion in JavaScript Addition

This repository demonstrates a common, yet subtle, error in JavaScript: unexpected type coercion during addition.

## The Problem

JavaScript's loose typing can lead to unexpected results when performing arithmetic operations. In this example, adding a number (5) and a string ('5') results in string concatenation rather than numerical addition.

## The Solution

To ensure numerical addition, explicitly convert the operands to numbers using functions such as `parseInt()` or `Number()`. 

## How to reproduce the bug
1. Clone the repository.
2. Open `bug.js`.
3. Run the JavaScript code using a Node.js environment, such as `node bug.js`.

## How to fix the bug
1. Open `bugSolution.js`.
2. Compare the implementation with `bug.js` to understand the corrected approach.
3. Run the corrected code using Node.js: `node bugSolution.js`.