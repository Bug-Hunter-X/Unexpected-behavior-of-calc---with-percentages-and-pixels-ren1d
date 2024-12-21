# Unexpected calc() Behavior in CSS

This repository demonstrates an uncommon issue encountered when using the `calc()` function in CSS with a mix of percentages and pixels.  The issue results in inconsistent rendering of element widths across different browsers.

## Problem

The CSS code attempts to set the width of an element to 50% of its parent's width, minus 10 pixels.  However, this calculation does not always produce the expected result, leading to layout discrepancies.

## Solution

The solution involves ensuring consistent unit handling within the `calc()` function. In this case, converting the pixel value to a percentage based on the parent element's width provides a more reliable and consistent result.