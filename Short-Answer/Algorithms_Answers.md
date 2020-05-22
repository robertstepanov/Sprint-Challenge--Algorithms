#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) This is a linear function and it's dependent on the value of n so O(n)

b) This is a iterative function that grows proportionally with the length of n so O(nlogn)

c) This is a recursive function that takes the same amount of time in each step so O(c)

## Exercise II

I would use a binary search to do this. O(logn)

1. Determine how many floors and then find the middle.
2. Drop an egg.
3. If egg breaks we can eliminate the floors above.
4. If egg doesn't break we can eliminate the floors below.
5. Find the middle of the floors above or below depending on results above.
6. Repeat the process until we find the correct floor.
