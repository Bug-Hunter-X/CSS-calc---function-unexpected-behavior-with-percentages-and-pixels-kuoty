# CSS calc() Unexpected Behavior

This repository demonstrates a bug where the CSS `calc()` function doesn't produce the expected result when combining percentages and other units (like pixels).

## Bug Description

The `calc()` function is designed to allow dynamic calculations within CSS. However, when used with percentages and fixed units, the results might be inconsistent across different browsers or situations.

## How to Reproduce

1.  Clone this repository.
2.  Open `bug.css` to see the problematic CSS code.
3.  Open `bugSolution.css` to see the fixed code.
4. Observe the difference in width calculations.

## Solution

The solution provided in `bugSolution.css` addresses the issue by ensuring proper order of operations and unit consistency within the `calc()` function. Sometimes, adding parentheses to clarify the order of operations can resolve the issue.

This demonstrates how seemingly simple CSS calculations can unexpectedly behave.