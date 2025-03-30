# HiTechDocTutorial - Tutorial 1: Collatz Conjecture Service

## Objective

In this tutorial, we will build a simple service that computes the number of steps it takes for a given positive integer to reach 1, following the rules of the Collatz conjecture. This is a classic problem in mathematics and will help us explore how AI can assist in coding tasks.

## The Collatz Conjecture

The Collatz conjecture is defined as follows:

1.  Start with any positive integer `n`.
2.  If `n` is even, divide it by 2 (`n = n / 2`).
3.  If `n` is odd, multiply it by 3 and add 1 (`n = 3n + 1`).
4.  Repeat steps 2 and 3 until `n` becomes 1.

The conjecture states that this process will eventually reach 1, no matter what positive integer you start with. While this hasn't been proven, it holds true for all numbers tested so far.

## Service Requirements

Our service will take a positive integer as input and return the number of steps it took to reach 1, according to the Collatz conjecture.

**Input:**

*   A positive integer `n` (e.g., 6, 10, 27).

**Output:**

*   An integer representing the number of steps it took for `n` to reach 1.

**Example:**

Let's trace the steps for `n = 6`:

1.  `n = 6` (even) -> `n = 6 / 2 = 3`
2.  `n = 3` (odd) -> `n = 3 * 3 + 1 = 10`
3.  `n = 10` (even) -> `n = 10 / 2 = 5`
4.  `n = 5` (odd) -> `n = 3 * 5 + 1 = 16`
5.  `n = 16` (even) -> `n = 16 / 2 = 8`
6.  `n = 8` (even) -> `n = 8 / 2 = 4`
7.  `n = 4` (even) -> `n = 4 / 2 = 2`
8.  `n = 2` (even) -> `n = 2 / 2 = 1`

It took 8 steps for `n = 6` to reach 1.

**Acceptance Criteria**
* the function name is `collatz_steps`
* the function takes in one argument `n`, which is the number to be computed
* the function returns an integer that is the number of steps to compute to one.
* the service will be written in python.

## Tutorial Steps

This tutorial will guide you through:

1.  Implementing the Collatz conjecture logic in Python without AI assistance.
2.  Using AI to suggest code improvements and optimizations.
3.  Debugging the code with the help of AI.
4.  Testing the function.

## Next Steps

In the next part of this tutorial, we will begin implementing the code and then we will explore how we can improve our code with the assistance of an AI coding peer.