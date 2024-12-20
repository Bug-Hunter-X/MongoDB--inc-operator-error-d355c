# MongoDB $inc operator error
This repository contains a simple example of an incorrect usage of the $inc operator in MongoDB update query. The $inc operator is used to increment or decrement a numeric value by a specified amount. The value to increment or decrement must be a number, not a string. 

## Bug Report
The bug is caused by passing a string value to the $inc operator. This results in an error.

## Solution
The solution is to pass a numeric value to the $inc operator.