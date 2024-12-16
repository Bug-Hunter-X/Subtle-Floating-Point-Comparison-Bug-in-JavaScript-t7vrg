# Subtle Floating-Point Comparison Bug in JavaScript

This repository demonstrates a common, yet subtle, bug in JavaScript related to comparing floating-point numbers for equality.

## The Bug

The `foo` function in `bug.js` attempts to compare two numbers for equality. However, due to the imprecise nature of floating-point representation, this comparison can fail unexpectedly when dealing with numbers that are not exactly representable.

## The Solution

The `bugSolution.js` file provides a solution using a tolerance value to handle the imprecision of floating-point numbers.  This approach determines if the difference between the two numbers is within an acceptable margin of error.