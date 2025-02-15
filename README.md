# Unhandled Modulo Operator Bug in JavaScript Calculator

This repository demonstrates a common error in JavaScript: failure to handle all possible cases within a `switch` statement.  The provided `operate` function handles addition, subtraction, multiplication, and division, but it throws an error if an unsupported operator is used.  The bug is that it doesn't handle the modulo operator (`%`).

The `bug.js` file contains the buggy code. The `bugSolution.js` file shows the corrected version.

## Bug
The original `operate` function lacks a `case` for the modulo operator (`%`).  This leads to an 'Invalid operator' error when trying to perform a modulo operation.

## Solution
The solution adds a `case '%' ` to the `switch` statement, handling modulo operations correctly. This ensures that the function handles all four basic arithmetic operations plus the modulo operator, making it more robust and complete.