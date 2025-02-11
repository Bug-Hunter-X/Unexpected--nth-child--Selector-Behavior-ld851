# Unexpected `nth-child` Selector Behavior

This repository demonstrates a subtle but potentially confusing issue with CSS's `nth-child` selector. When used in conjunction with other selectors, it can produce unexpected results.

The `bug.css` file contains the CSS code exhibiting the issue. The `bugSolution.css` file provides the corrected version.

## Problem
The goal is to style every other list item, starting from the second item.  The CSS in `bug.css` does not achieve this. Instead, it styles every other item beginning with the first.

## Solution
The `bugSolution.css` file presents a modified selector that correctly styles every other list item, beginning from the second.