# JavaScript: Incorrect Handling of Undefined in Addition Function

This repository demonstrates a common, subtle bug in JavaScript related to how undefined values are handled during arithmetic operations, specifically addition.

## Bug Description

The provided JavaScript function `foo` attempts to add two numbers. It correctly handles `null` values by returning 0. However, it fails to correctly handle `undefined` values, resulting in `NaN` (Not a Number).  This can lead to unexpected behavior in applications.

## Bug Solution

The solution involves explicitly checking for `undefined` values and handling them appropriately, similar to how null values were already handled.