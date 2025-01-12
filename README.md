# CSS Specificity Bug

This repository demonstrates an uncommon bug related to CSS selector specificity.  The bug arises from a misunderstanding of how CSS specificity determines which styles are applied when there are conflicting styles.

The `bug.css` file contains the problematic CSS code. The `bugSolution.css` file offers a solution and explanation.

## Bug Description
The bug involves unexpected style overriding due to the higher specificity of certain CSS selectors.  This can lead to unexpected visual results, especially when working with complex CSS stylesheets.

## Solution
Understanding CSS specificity is critical in avoiding this type of bug.  The solution involves carefully reviewing selector specificity rules and potentially refactoring CSS to improve readability and predictability.