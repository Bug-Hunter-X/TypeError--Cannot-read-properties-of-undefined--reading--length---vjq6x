# JavaScript Bug: TypeError: Cannot read properties of undefined (reading 'length')

This repository demonstrates a common JavaScript error: `TypeError: Cannot read properties of undefined (reading 'length')`.  The error occurs when attempting to access the `length` property of a variable that holds an undefined value.  This often happens when a function expects an object with a `length` property but receives `undefined` as input.

The `bug.js` file contains the problematic code. The `bugSolution.js` file provides a solution to handle the undefined case gracefully.