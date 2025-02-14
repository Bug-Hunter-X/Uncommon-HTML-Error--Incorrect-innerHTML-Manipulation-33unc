# Uncommon HTML Error: Incorrect innerHTML Manipulation

This repository demonstrates a common yet subtle error when manipulating the `innerHTML` property of an HTML element using Javascript.  The issue arises from directly accessing and modifying `innerHTML` without performing necessary null checks to ensure that the element actually exists in the DOM before attempting to access its `innerHTML` property. This can result in a runtime error (TypeError: Cannot read properties of null (reading 'innerHTML')) if the element with the specified ID is not found.

The `bug.html` file contains the erroneous code, while `bugSolution.html` provides the corrected version, showing how to implement proper null checks for robust and error-free code.