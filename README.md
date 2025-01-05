# Uncommon HTML Bug: innerHTML with Non-String

This repository demonstrates an uncommon bug in HTML related to the `innerHTML` property.

The bug arises from attempting to set the `innerHTML` property of an element to a non-string value (in this case, a number).
While some browsers might implicitly convert the number to a string, this is not guaranteed across all browsers and versions, leading to inconsistencies and unexpected behavior.

The `bug.html` file contains the erroneous code, and `bugSolution.html` provides the corrected version.  Always ensure you're setting `innerHTML` to a string value for consistent results.