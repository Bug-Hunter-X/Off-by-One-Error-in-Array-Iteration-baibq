# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over arrays. The error occurs when the loop condition incorrectly includes the index equal to the array's length. This leads to an `ArrayIndexOutOfBoundsException` because arrays are zero-indexed.  The solution shows how to correct this by changing the loop condition to `i < arr.length`. 