# Hidden Div Bug

This repository demonstrates a common logic error in HTML/JavaScript where a div element is hidden using JavaScript, but there's no mechanism provided to make it visible again. The bug showcases the importance of considering all states in your application logic, ensuring elements remain accessible.

## Bug Description
The `bug.html` file contains a simple HTML page with a div and a button. Clicking the button hides the div using `style.display = "none";`.  The problem is that there's no subsequent code to reverse this action, leading to the div remaining permanently hidden after the button is clicked.

## Solution
The `solution.html` file demonstrates the solution by adding a condition to toggle the visibility of the div, allowing the user to show and hide it repeatedly.