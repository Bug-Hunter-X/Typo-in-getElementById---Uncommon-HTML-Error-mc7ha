# Uncommon HTML Error: Typo in getElementById

This repository demonstrates a subtle but common error in JavaScript when interacting with HTML elements. The error involves a simple typo in the `getElementById` method, which often leads to unexpected behavior and prevents the code from working as intended.

## The Bug

The `bug.html` file contains a simple HTML structure with a div element. The JavaScript code attempts to change the innerHTML of this div. However, there is a typo in the `getElementById` function name, leading to the error.

## The Solution

The `bugSolution.html` file provides the corrected version. The typo is fixed, so the JavaScript code works correctly, modifying the content of the div element.

## How to Reproduce

1. Open `bug.html` in a web browser.
2. Observe that the text within the div doesn't change.
3. Open `bugSolution.html`. The text will be correctly changed.