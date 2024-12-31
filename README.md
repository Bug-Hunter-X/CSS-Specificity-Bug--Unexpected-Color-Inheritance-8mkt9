# CSS Specificity Bug

This repository demonstrates a common yet often overlooked bug in CSS: unexpected styling due to selector specificity. The bug arises when multiple CSS rules target the same element, and the specificity of the selectors determines which rule takes precedence.

## Bug Description
The `bug.css` file contains two conflicting CSS rules that affect the color of paragraph elements (`<p>`).  The specificity of the selector `div p` is higher than `p`, causing unexpected behavior when a `<p>` element is nested within a `<div>`.

## Solution
The `bugSolution.css` file demonstrates how to correct this behavior, either by adjusting selector order or making one selector more specific than the other to ensure expected behavior.