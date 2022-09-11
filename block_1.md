<flow9 language introduction block>

1. Write a function that converts an array of integers into an array of strings, for example: [1, 2, 3] to ["1", "2", "3"], print this array. Use the functions: map, i2s, strGlue, println.

2. Write a function that counts the sum of integers in an array: [1, 2, 3] in 6. Use the functions: fold.

3. Write a function, fib(n : int) -> [int], calculating the n first Fibonacci numbers: 0, 1, 1, 2, 3, 5, .... Make it a) recursive b) with tail recursion c) using array references, complexity O( n ). Use: fold, concat, refArrayPush

4. Given an array of integers [n_1,...,n_k] and the number m. Find all pairs of indices (i, j) such that n_i + n_j == m. Function signature: inds(a : [int], m : int) -> [Pair<int, int>]. Complication: Make this complexity function O(n log(n)), not O(n^2). Use the functions: fold, makeTree, setTree, lookupTree.
