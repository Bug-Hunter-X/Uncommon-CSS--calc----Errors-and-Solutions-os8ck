# Uncommon CSS `calc()` Errors and Solutions

This repository demonstrates some uncommon errors that can occur when using the CSS `calc()` function and provides solutions for resolving them.

**Common Issues with `calc()`**

* **Inconsistent Units:** Mixing units (e.g., `px` and `%`) within a single `calc()` expression without proper conversion can lead to unpredictable results. 
* **Syntax Errors:**  Missing spaces, incorrect operators, or typos in the calculation can cause errors. 
* **Nested `calc()` Expressions:** Nesting `calc()` expressions without proper care can lead to parsing issues.
* **Unsupported Units:** Using units not supported by the browser in your calculations will cause problems.

**Solutions and Best Practices**

* **Ensure Consistent Units:**  Use the same unit throughout your `calc()` expression, or perform explicit unit conversions.
* **Double-Check Syntax:** Carefully check the syntax of your `calc()` expression for any errors such as missing spaces, or incorrect operators.
* **Avoid Deep Nesting:** If possible, avoid deeply nested `calc()` expressions to improve readability and reduce the risk of errors.
* **Use Supported Units:** Stick to units that are widely supported by browsers.

The `bug.css` file shows examples of problematic code, and `bugSolution.css` offers corrected versions.