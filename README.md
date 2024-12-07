# Unexpected runtime error with type guards and undefined values

This repository demonstrates an uncommon error in TypeScript related to type guards and the handling of `null` and `undefined` values.

## The Bug

The `greet` function attempts to handle both string and null inputs. While it correctly handles `null`, it fails to handle `undefined`, resulting in a runtime error.

## Solution

The solution involves explicitly checking for both `null` and `undefined` values in the type guard condition.