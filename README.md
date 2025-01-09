# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is designed to increment a numeric field.  Attempting to increment a field with a non-numeric value results in an error or unexpected behavior.

## Bug
The `bug.js` file contains code that attempts to increment a counter field using a string value. This will lead to an error.

## Solution
The `bugSolution.js` file shows the corrected code, ensuring that the value provided to `$inc` is a number.