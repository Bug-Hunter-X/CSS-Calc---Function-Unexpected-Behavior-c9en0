# CSS Calc() Function Unexpected Behavior

This repository demonstrates a common error encountered when using the `calc()` function in CSS, specifically within flexbox layouts.  The bug showcases how an improper use of `calc()` can result in unexpected and inconsistent layout behavior.

The `bug.css` file contains the erroneous CSS code. The `bugSolution.css` file demonstrates the corrected implementation.

**Problem:**  The `calc()` function, intended for dynamic calculations, can produce unpredictable outcomes if not carefully implemented, particularly when combined with percentage values and relative units within flexbox containers lacking defined dimensions.