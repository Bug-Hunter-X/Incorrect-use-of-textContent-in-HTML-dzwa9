# Incorrect use of textContent in HTML

This repository demonstrates an uncommon bug in HTML related to the `textContent` property.  The code incorrectly attempts to retrieve the entire HTML content of a div element using `textContent`, which only returns the text content of direct child elements, excluding any HTML tags within the div. The solution shows the correct method using `innerHTML` to get the entire HTML content.

## Bug
The `bug.html` file contains the incorrect code that only retrieves the text content of the direct child element of the div and not the whole content of the div.

## Solution
The `bugSolution.html` file demonstrates the correct way of retrieving the complete innerHTML of a div element by using the `innerHTML` property.