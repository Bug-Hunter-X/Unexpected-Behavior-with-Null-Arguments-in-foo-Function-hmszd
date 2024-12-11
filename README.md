# Unexpected Behavior with Null Arguments in foo Function

This repository demonstrates a common JavaScript bug involving unexpected behavior when null values are passed as arguments to a function.  The `foo` function silently returns without explicit null handling, leading to potential issues.

## Bug Description

The `foo` function does not handle `null` arguments gracefully. When either `a` or `b` is `null`, the function simply returns without any error handling or informative message. This can lead to subtle bugs that are difficult to trace.

## Solution

The solution involves explicitly checking for null values and handling them appropriately.  This might involve throwing an error, returning a default value, or logging a warning.