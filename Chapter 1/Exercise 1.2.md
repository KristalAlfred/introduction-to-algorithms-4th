**1.2-1: *Give an example of an application that requires algorithmic content at the application level, and discuss the function of the algorithms involved.***

Answer: An audio file size calculator. It's a really simple one, just a calculation. 

**1.2-2: *Suppose that for inputs of size n on a particular computer, insertion sort runs in 8 * n^2 steps and merge sort runs in 64 n * lg(n) steps. For which values of n does insertion sort beat merge sort?***

Answer: 8 n^2 < 64 * n * lg(n)  
8 * n < 64 * lg(n)  
1/8 * n < lg(n)  
1/8 < lg(n) / n  
n < 8 lg(n)  
n < lg(n^8)  
2^n < n^8  
Solved visually to be true for:  
2 <= n <= 43


**1.2-3: *What is the smallest value of n such that an algorithm whose running time is 100n2 runs faster than an algorithm whose running time is 2^n on the same machine?***

Answer: 100n^2 = 2^n  
Solved geometrically to be roughly 14.32  
Answer is therefore n = 15

