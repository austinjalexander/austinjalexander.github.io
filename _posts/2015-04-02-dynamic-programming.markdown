---
layout: post
title:  "Dynamic Programming"
date:   2015-04-02 19:27:41
categories: dynamic programming optimization greedy algorithms
---
[UNDER CONSTRUCTION]

Straight out of MIT's algorithm bible (CLRS) [1], the following offers a simple examination and summary of that tome's chapters on dynamic programming and greedy algorithms.

Dynamic programming is a potential solution method to a given problem when that problem has subproblems, which overlap. Since this overlap exists, upon finding a solution for a particular subproblem, a dynamic-programming algorithm saves the answer in a table.

CLRS offers the following sequence of steps for developing a dynamic programming algorithm:

1. Characterize the structure of an optimal solution
2. Recursively define the value of an optimal solution
3. Compute the value of an optimal solution, typically in a bottom-up fashion
4. Construct an optimal solution from computed information


---
[1] T. Cormen, C. Leiserson, R. Rivest and C. Stein, _Introduction to Algorithms (3rd ed.)_. Cambridge, MA: MIT Press, 2009.
