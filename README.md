Prime Number Checker
A Prime Number Checker is a program or algorithm that determines whether a given number is prime or composite.

Definition of a Prime Number
A prime number is a natural number greater than 1 that has exactly two divisors: 1 and itself.
Examples: 2, 3, 5, 7, 11, 13, 17, ...

A composite number has more than two divisors.
Examples: 4 (2×2), 6 (2×3), 8 (2×4), 9 (3×3), 10 (2×5), ...

Algorithm for Checking Prime Number
There are multiple ways to check if a number is prime. Here are the most common approaches:

1. Basic Trial Division (Naive Approach)
Check divisibility from 2 to (n-1).
If n is divisible by any number in this range, it is not prime.
Time Complexity: 
𝑂(𝑛)
O(n) (inefficient for large numbers)
