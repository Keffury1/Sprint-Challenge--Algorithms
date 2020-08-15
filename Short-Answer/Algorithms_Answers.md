#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) 0(n) - The while loop causes this runtime


b) 0(n^2) - The while loop inside the for loop causes this runtime


c) 0(1) - The lack of iteration causes this runtime

## Exercise II

I would simply use binary search with recursion to locate the index in which the correct floor is found.
First, I would ensure the count is not 0 as our base case.
Second, I would set up my recursive case which is the case in which f is not found. If f is found, I simply return f.
The runtime for binary search is 0(1).