# JavaScript Loose Equality Bug

This repository demonstrates a common JavaScript bug related to loose equality (`==`) comparisons.  The bug arises from the fact that Javascript uses type coercion in these comparisons, which can lead to unexpected results.

## Bug Description
The provided code uses loose equality to compare two values. It fails when comparing values of different types. 

## Bug Solution
The solution utilizes strict equality (`===`) to avoid type coercion.  This ensures that the comparison is true only when both the values and their types match. 

## How to Run
1. Clone the repository.
2. Open `bug.js` and `bugSolution.js` in your preferred text editor.
3. Run the Javascript files in a browser's console or Node.js to see the comparison results. 