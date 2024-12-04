# Java Off-by-One Error Example

This repository demonstrates a common off-by-one error in Java when iterating over an array. The code attempts to access an array element beyond its bounds, resulting in an `ArrayIndexOutOfBoundsException`.

The `bug.java` file contains the erroneous code. The `bugSolution.java` file provides a corrected version.

## How to reproduce the bug

1. Compile the `bug.java` file using a Java compiler (javac).
2. Run the compiled code (java MyClass).
3. Observe the `ArrayIndexOutOfBoundsException`.

## Solution

The solution involves correcting the loop condition in the `for` loop to ensure it does not exceed the valid index range of the array.  The corrected code is in `bugSolution.java`.