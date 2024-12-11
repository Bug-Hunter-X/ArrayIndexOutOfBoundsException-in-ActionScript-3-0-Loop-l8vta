# ActionScript 3.0 ArrayIndexOutOfBoundsException Bug

This repository demonstrates a common error in ActionScript 3.0: the `ArrayIndexOutOfBoundsException`.  This exception occurs when you attempt to access an array element using an index that is outside the valid range of the array (0 to array.length - 1).

The `bug.as` file contains code that reproduces this error. The `bugSolution.as` file provides a corrected version.

## How to Reproduce

1.  Clone this repository.
2.  Compile and run `bug.as` using an ActionScript 3.0 compiler (e.g., Adobe Flex SDK, Apache Flex SDK).
3. Observe the `ArrayIndexOutOfBoundsException` error.

## Solution

The solution involves carefully checking the loop counter to ensure it remains within the bounds of the array.