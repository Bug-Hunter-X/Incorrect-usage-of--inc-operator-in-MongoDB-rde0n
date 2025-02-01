# Incorrect Usage of $inc Operator in MongoDB

This repository demonstrates a common error when using the `$inc` operator in MongoDB: providing a string value instead of a number. The `$inc` operator is used to increment a numerical field by a specified value. If a non-numeric value is provided, the operation will fail.

## Bug
The bug lies in the incorrect usage of the `$inc` operator.  The code attempts to increment the `counter` field by the string value "1" instead of the numerical value 1.

## Solution
The solution involves providing a numerical value to the `$inc` operator. The updated code uses the correct numerical value 1, ensuring successful incrementation of the `counter` field.
