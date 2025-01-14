# CSS :has() Pseudo-class Issue with Non-Direct Child Selectors

This repository demonstrates an uncommon issue with the CSS `:has()` pseudo-class when used with selectors that don't target direct child elements.  Some browsers might not correctly interpret the selector if the targeted element is a more distant descendant.

## Problem

The `bug.css` file contains CSS that attempts to target a container element based on the presence of a distant descendant element.  This might not work in all browsers.

## Solution

The `bugSolution.css` file provides a solution that utilizes a more compatible selector to reliably target the container element.

## Setup

1. Clone the repository.
2. Open `index.html` in a web browser.
3. Observe the behavior in different browsers to see the inconsistencies.
