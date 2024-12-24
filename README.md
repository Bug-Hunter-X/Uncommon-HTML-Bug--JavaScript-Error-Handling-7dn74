# Uncommon HTML Bug: JavaScript Error Handling
This repository demonstrates a common yet easily overlooked JavaScript error when interacting with the DOM in HTML.  The error occurs when attempting to access a DOM element that doesn't exist before the script executes.

## Bug Description
The `bug.html` file contains a simple HTML page with a `div` element. A JavaScript event listener is attached to this element.  However, if the element is not found (perhaps due to a typo or asynchronous loading), the script will throw an error.

## Solution
The `bugSolution.html` file provides a solution by incorporating error handling to prevent the script from crashing. It checks if the element exists before attempting to access its properties.

This example emphasizes the importance of robust error handling in JavaScript when working with the DOM, ensuring graceful degradation and preventing unexpected crashes.