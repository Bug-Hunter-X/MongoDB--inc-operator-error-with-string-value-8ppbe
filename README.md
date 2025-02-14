# MongoDB $inc operator error with string value

This repository demonstrates an incorrect usage of the `$inc` operator in a MongoDB update query and provides a solution to fix the error.

The error occurs when a non-numeric value (in this case, a string) is passed to the `$inc` operator. This leads to an error or unexpected behavior in the update operation.

The solution involves ensuring that the value passed to the `$inc` operator is a valid numeric value (integer or float).
