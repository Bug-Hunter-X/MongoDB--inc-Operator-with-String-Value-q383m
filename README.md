# MongoDB $inc Operator with String Value
This example demonstrates an incorrect usage of the `$inc` operator in MongoDB.  The `$inc` operator is used to increment a numerical field by a specified value. However, attempting to increment with a string will result in an error or unexpected behavior. The solution shows how to correct this error and increment the field correctly.

## Bug
The provided code snippet shows an incorrect usage of the `$inc` operator where a string value is provided to increment the `counter` field. This is incorrect as `$inc` only works with numbers. 

## Solution
The solution shows the correct usage of the `$inc` operator using a numerical value to increment the field successfully.