# Groovy NullPointerException in Arithmetic Operations

This example demonstrates a common error in Groovy related to null values in arithmetic operations. Groovy's dynamic typing can lead to unexpected behavior if null values are not explicitly handled.

## Problem
The `calculate` function performs addition. However, if either `a` or `b` is null, a `NullPointerException` might occur in certain scenarios.  Even without the exception, the result might not be what is expected.

## Solution
The solution demonstrates how to explicitly check for null values before performing the addition, which avoids the potential `NullPointerException` and produces more predictable results.