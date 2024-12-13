# Unexpected Layout Due to Negative `calc()` Result

This repository demonstrates a common CSS bug involving the `calc()` function.  Incorrect usage can lead to negative values, causing unexpected layout shifts or rendering issues. The solution provides a corrected implementation.

## Bug

The `bug.css` file contains CSS that attempts to calculate the width of an element. However, due to an error in the calculation, the result is negative, resulting in the element not being displayed correctly.

## Solution

The `bugSolution.css` file provides a corrected version of the CSS, ensuring the `calc()` function produces a positive value.