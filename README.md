# Unexpected Behavior in CSS calc() Due to Spaces

This repository demonstrates an uncommon CSS bug related to the use of spaces within the `calc()` function.  Incorrect spacing can lead to unexpected rendering of elements.

## Bug Description
The `calc()` function in CSS is designed to allow dynamic calculations of lengths and other CSS values. However, extra spaces around the operators (+, -, *, /) within the `calc()` function can cause parsing errors and unexpected behavior.  The bug is subtle and easy to miss.

## How to Reproduce
1. Open `bug.css`
2. Observe the incorrect rendering of the element due to spaces in the `calc()` function.
3. Open `bugSolution.css`
4. Observe the correct rendering after removing the extra spaces.

## Solution
Remove any unnecessary spaces around the operators within the `calc()` function to ensure correct calculation and rendering.