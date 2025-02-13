# Uncommon HTML Bug: getElementById() Failure with Space in ID

This repository demonstrates a subtle bug that can occur in HTML when using `document.getElementById()` to select an element with a space in its ID.

## Bug Description
The `document.getElementById()` method is case-sensitive and fails when there is a space in the ID.  This leads to the element not being found, even though the element exists in the HTML.

## Solution
The solution involves using a valid ID without spaces, or modifying the JavaScript to handle the case where the element is not found gracefully.

## How to reproduce
1. Clone the repository.
2. Open `bug.html` in a web browser. 
3. You will see that the text within the div remains visible because the Javascript failed to find the element.
4. Open `bugSolution.html` to see the corrected version.
