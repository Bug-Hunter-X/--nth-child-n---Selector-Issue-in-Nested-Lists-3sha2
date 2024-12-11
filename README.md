# :nth-child(n) Selector Issue in Nested Lists

This repository demonstrates a problem with the CSS `:nth-child(n)` selector when used with nested lists. The expected styling of every other list item is not applied correctly to nested list elements.

## Bug Report

The `bug.css` file contains the CSS code that exhibits the issue.  The `bug.html` file shows the HTML structure that this CSS is applied to.  The problem is that the nested list items do not follow the `:nth-child(2n)` rule, despite expectations.

## Solution

The `bugSolution.css` file provides a corrected CSS approach to style every other list item, regardless of nesting level, addressing the problem correctly.  This demonstrates how to achieve the desired styling consistently across list nesting.