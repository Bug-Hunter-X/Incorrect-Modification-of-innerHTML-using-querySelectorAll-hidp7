# Incorrect innerHTML Modification with querySelectorAll

This example demonstrates a common mistake when using `querySelectorAll` in JavaScript within an HTML context.  `querySelectorAll` returns a NodeList, which doesn't have an `innerHTML` property directly.  Attempting to modify `innerHTML` on the NodeList will result in an error.

The `bug.html` file shows the problematic code. The `bugSolution.html` file shows the corrected code.