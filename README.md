# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over an array. The error occurs because the loop condition `i <= arr.length` attempts to access an index beyond the array's bounds, causing an `ArrayIndexOutOfBoundsException`.

The solution involves correcting the loop condition to `i < arr.length` to ensure that the loop terminates before accessing an invalid index.