# Dart IndexError Bug

This repository demonstrates a common coding error in Dart: attempting to access an element in a list using an index that is out of bounds.  This leads to an `IndexOutOfRangeException`.

The `bug.dart` file contains the buggy code, while `bugSolution.dart` provides a corrected version.

## Bug Description
The error occurs when trying to access an element at an index equal to or greater than the length of the list.  If the list is empty, attempting to access any index will throw the exception.

## Solution
The solution involves adding a check to ensure the list is not empty before accessing elements.  It is also wise to use null-safety features.