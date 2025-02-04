# Permanently Hidden Div Element
This repository demonstrates an uncommon HTML bug where a div element becomes permanently hidden after a button click. The issue arises from missing code to restore the element's visibility after it's initially hidden.

## Bug Description
The `myFunction()` in `bug.html` hides the div element with id "myDiv" but lacks the necessary code to show it again. This results in the div remaining permanently hidden after the button click. 

## Solution
The `bugSolution.html` provides a corrected version with added functionality to re-display the hidden div after a delay, resolving the permanent hiding issue. 