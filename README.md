# MongoDB $inc Operator Bug with Nested Fields

This repository demonstrates a common bug encountered when using the MongoDB `$inc` operator to update nested fields. The incorrect usage can lead to unexpected results or no changes at all.

## Problem

The `$inc` operator is used to increment a numerical field. However, when attempting to increment a nested field, there is a common error:

- Incorrect dot notation or structure might prevent the update from occurring correctly. 

The `bug.js` file showcases this error, resulting in the nested field not being incremented as expected.

## Solution

The correct way to increment a nested field is shown in `bugSolution.js`. This file demonstrates the correct implementation of the update.