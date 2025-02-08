# CSS Specificity and Inheritance Bug

This repository demonstrates a subtle bug related to CSS specificity and inheritance.  The issue involves unexpected style overriding where a more specific rule is unexpectedly overridden by a less specific one.

## Bug Description
The `bug.css` file contains CSS code that exhibits this unexpected behavior. A higher-specificity style rule is inexplicably overridden by a lower-specificity one.  This is contrary to standard CSS specificity rules.

## Solution
The `bugSolution.css` file provides a solution to address the unexpected behavior.  It employs techniques that enhance specificity to ensure that the intended styles are applied correctly.

## Setup
To reproduce the bug and test the solution, simply include the corresponding CSS file in your HTML document and observe the styling of the `<h1>` element within the `.container` class.  The differences in rendered styles will highlight the bug and the effectiveness of the solution.