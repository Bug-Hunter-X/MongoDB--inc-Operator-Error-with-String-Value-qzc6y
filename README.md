# MongoDB $inc Operator Error with String Value

This example demonstrates an error that can occur when using the MongoDB `$inc` operator with an incorrect data type. The `$inc` operator is used to increment a numeric field by a specified value. However, if a string is provided as the increment value instead of a number, the operation will fail, and it will not increment the field correctly. This can lead to unexpected behavior in your application.

The `bug.js` file contains the incorrect usage of the `$inc` operator, and the `bugSolution.js` provides the correct implementation.