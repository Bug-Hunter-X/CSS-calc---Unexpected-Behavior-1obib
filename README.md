# CSS calc() Unexpected Behavior

This repository demonstrates a common yet easily overlooked issue with the CSS `calc()` function: inconsistent unit handling and unexpected operator precedence.  The `bug.css` file contains the problematic CSS, while `bugSolution.css` provides a corrected version.  The issue stems from misinterpreting the context of percentages and improper unit mixing within the `calc()` function.