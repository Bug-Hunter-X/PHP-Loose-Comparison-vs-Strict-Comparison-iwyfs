# PHP Loose Comparison vs Strict Comparison

This example demonstrates the difference between loose comparison (==) and strict comparison (===) in PHP. Loose comparison checks for equality without considering type, while strict comparison checks for both value and type equality. This difference can lead to unexpected behavior if not handled carefully.

The `bug.php` file contains a function that uses loose comparison, which can return unexpected results when comparing values of different types.  The `bugSolution.php` file demonstrates how to use strict comparison to avoid such issues.