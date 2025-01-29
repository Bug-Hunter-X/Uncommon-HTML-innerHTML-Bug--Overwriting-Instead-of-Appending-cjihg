# Uncommon HTML Bug: innerHTML Overwriting
This repository demonstrates a subtle bug related to the use of `innerHTML` in HTML for dynamically appending content.

The `bug.html` file showcases the problem where the intended appending operation using `innerHTML +=` actually overwrites the existing content. This is a common mistake developers might encounter when dynamically updating HTML structures.

The `bugSolution.html` file presents the correct approach for appending content using `insertAdjacentHTML`.  This method avoids the accidental overwriting of existing content.

This example is valuable for understanding the nuances of dynamic HTML updates and avoiding similar issues in web development projects.