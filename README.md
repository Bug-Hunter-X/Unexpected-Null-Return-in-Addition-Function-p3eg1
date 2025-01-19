# Unexpected Null Return in Addition Function

This repository demonstrates a common, yet subtle bug in JavaScript related to null value handling within a simple addition function.  The function `foo` is designed to add two numbers. However, it prematurely returns `null` if either of the inputs is `null`, even if the other input is a valid number. This behavior might not be the intended functionality, as a more robust approach could handle `null` values differently (e.g., treat them as 0).  The `bugSolution.js` file offers a corrected version.

## How to Reproduce

1. Clone the repository.
2. Open `bug.js` and observe the original faulty function.
3. Run the code using a Node.js environment (or any JavaScript environment) to see the unexpected null returns.
4. Compare to `bugSolution.js` to see the improved, more robust handling of null values.