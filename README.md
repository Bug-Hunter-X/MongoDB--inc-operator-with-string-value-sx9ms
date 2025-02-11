# MongoDB $inc Operator Error
This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries.  The error occurs when a string value is passed to `$inc` instead of a number.

## Bug Description
The provided code attempts to increment the `count` field by '10' (string) instead of 10 (number).  MongoDB expects a number for the increment value. This leads to unexpected results or an error.

## Solution
The solution involves correcting the usage of the `$inc` operator to use a numerical value for the increment.
