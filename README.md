# JavaScript Function's Unexpected Behavior with Undefined Input

This repository demonstrates an uncommon bug in JavaScript related to how functions handle undefined input when expecting null.  The function `foo` is intended to handle null values gracefully, but it fails to account for undefined input. This leads to unexpected NaN (Not a Number) results.

The `bug.js` file contains the buggy code, while `bugSolution.js` provides a corrected version demonstrating how to handle both null and undefined inputs robustly.