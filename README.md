# ActionScript 3 Undeclared Variable Error

This repository demonstrates a common ActionScript 3 error: attempting to use a variable that hasn't been declared or initialized within the current scope.  The `bug.as` file shows the problematic code, while `bugSolution.as` provides the corrected version.

## Problem

In ActionScript 3, variables must be declared before use.  If you attempt to use a variable that hasn't been explicitly declared, the compiler will throw an error.

## Solution

Ensure that all variables are properly declared before use within their scope (function, class, etc.).  If the variable's value depends on external factors, initialize it with a default value, or use a conditional to handle scenarios where the variable might not yet be defined. 

## How to reproduce the bug:
1. Compile the code in `bug.as` using an ActionScript 3 compiler (like the one included with FlashDevelop or Adobe Animate). 
2. Observe the compiler error indicating that `someVariable` is undefined.