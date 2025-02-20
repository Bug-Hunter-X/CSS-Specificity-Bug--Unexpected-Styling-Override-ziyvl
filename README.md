# CSS Specificity Bug

This repository demonstrates a common CSS bug related to specificity.  A more specific selector unintentionally overrides a less specific selector, leading to unexpected styling.

The `bug.css` file contains the problematic CSS.  The `bugSolution.css` file provides a solution.

## Bug Description

The issue arises from conflicting selectors where a more specific one unintentionally overrides a less specific one, resulting in the styles not rendering as intended. Understanding and using the correct CSS specificity rules is essential to prevent this.