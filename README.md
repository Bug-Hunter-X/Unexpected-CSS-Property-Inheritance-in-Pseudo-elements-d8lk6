This repository demonstrates an uncommon CSS bug related to property inheritance from parent elements to pseudo-elements.  The bug manifests as unexpected styling behavior in the pseudo-element (:before or :after) despite explicit styling within the pseudo-element declaration. The issue is not consistently reproducible across all browsers, highlighting a subtle incompatibility or edge case in CSS rendering engines.

The `bug.css` file contains the buggy code, showcasing the unexpected property inheritance. The `bugSolution.css` file offers a solution to mitigate the issue by using more specific selectors or explicitly resetting inheritable properties in the pseudo-element declaration.