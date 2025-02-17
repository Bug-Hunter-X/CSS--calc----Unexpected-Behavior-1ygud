# CSS `calc()` Unexpected Behavior

This repository demonstrates a common issue with the CSS `calc()` function where unexpected results can occur if the parent element's dimensions aren't explicitly defined.

## Problem

The `calc()` function is a powerful tool for dynamic calculations within CSS. However, if the parent element lacks a defined width or height, calculations involving percentages can behave unexpectedly.

## Solution

Ensure the parent element has an explicitly defined width or height. This can be achieved through various methods, such as setting a fixed width or height, using `width: 100%`, or applying other layout techniques like flexbox or grid.

This repository provides example CSS code demonstrating the problem and its solution.