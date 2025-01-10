# CSS Float Layout Bug

This repository demonstrates a common issue encountered when using the `float` property in CSS without explicitly setting the width of the parent container. The bug occurs when the width of the parent element is not defined, leading to unexpected layout behavior.

## Bug Description

The `bug.css` file contains CSS code that attempts to create two divs, each occupying 50% of the parent's width. However, due to the undefined width of the parent, the divs don't render correctly in some browsers.

## Solution

The `bugSolution.css` file provides a solution to this problem by explicitly defining the width of the parent container.  This ensures that the percentage widths of the child divs are correctly calculated and the layout renders as expected.