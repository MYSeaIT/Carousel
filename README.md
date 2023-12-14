# Project Title
Simple Carousel Project

## Overview
This project is a simple carousel for displaying products. The carousel allows users to navigate through products using left and right buttons.

## Development Process
1. Created the HTML structure for the carousel in `index.html` (See file_context_0).
2. Styled the carousel using SCSS in `style.scss` (See file_context_1).
3. Implemented the carousel functionality using JavaScript in `script.js` (See file_context_3).

## Encountered Errors
- Issue: Misalignment of product items in the carousel
  - Solution: Adjusted the CSS properties for the product items to ensure proper alignment and spacing.

- Issue: Incorrect calculation of the number of carousel slides
  - Solution: Used the `Math.ceil` function to properly calculate the number of carousel slides based on the total number of products.

- Issue: Unexpected behavior when navigating the carousel
  - Solution: Implemented boundary checks and conditional statements to handle edge cases when navigating the carousel.

## Functionalities
- The carousel allows smooth left and right navigation through the product items.
- The carousel UI is responsive and handles varying numbers of products gracefully.

