# Block Scope in JavaScript with let

This repository demonstrates the concept of block scope in JavaScript using the `let` keyword.  The example shows how variables declared with `let` are only accessible within the block of code where they are defined.  This behavior is different from variables declared with `var`, which have function scope.

## Bug

The provided code snippet utilizes `let` to demonstrate block scope. The inner `let x = 20;` creates a new variable `x` within the `if` block that is different from the `let x = 10;` declared outside. 

## Solution

The solution file illustrates how `let` properly enforces block scope, leading to the expected output. The inner `x` is confined within its `if` block and does not alter the outer `x`. 