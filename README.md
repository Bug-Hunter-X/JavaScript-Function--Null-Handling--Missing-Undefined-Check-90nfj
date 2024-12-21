# JavaScript Function: Null Handling, Missing Undefined Check

This repository demonstrates a common JavaScript coding error involving null handling. The provided code correctly handles null values, but it omits handling for undefined values, which can lead to unexpected behavior or runtime errors.

## Bug Description
The `foo` function handles null values gracefully. However, if either `a` or `b` is undefined, the function will throw a TypeError because the `+` operator cannot be applied to `undefined`.

## Bug Solution
The improved version checks for both `null` and `undefined` before attempting the addition operation. This makes the function more robust and prevents potential errors.