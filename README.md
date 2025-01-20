# Incorrect Use of 'Img' Attribute in Ada

This example demonstrates a common error in Ada programming: attempting to use the `'Img` attribute (which is for obtaining the string representation of an enumeration literal) on an integer type.  This will result in a compilation error.

The solution involves using `Ada.Text_IO.Put` or `Ada.Text_IO.Put_Line` with the integer value directly, or converting the integer to a string using another method.

The files included are:

- `bug.ada`: Contains the erroneous code.
- `bugSolution.ada`:  Provides the corrected code.