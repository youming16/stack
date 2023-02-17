---
title: Dynamic programming
description: How dynamic programming solve problem for us
slug: (○'◡'○)
date: 2023-02-07 00:00:00+0000
categories:
    - Data Structure
tags:
    - dynamic programming
---



# What it is that?
Dynamic Programming is a technique in computer programming that helps to efficiently solve a class of problems that have **overlapping** subproblems and optimal substructure property.

# Pseudocode
Fibonacci:
```
var m = map(0 → 0, 1 → 1)
function fib(n)
    if key n is not in map m 
        m[n] = fib(n − 1) + fib(n − 2)
    return m[n]
```

# DP vs Recursion
Dynamic programming is mostly applied to recursive algorithms. 

But not all problems that use recursion can use Dynamic Programming. **Unless there is a presence of overlapping subproblems** like in the fibonacci. An Recursion can only reach the solution using a divide and conquer approach.

e.g. Like Merge Sort cannot use Dynamic Programming, because the subproblems are not overlapping in any way.

# DP vs Greedy Algorithm
Greedy Algorithms and DP they are **both tools for optimization**.

However, greedy algorithms look for **locally** optimum solutions (Global optimum). Hence greedy algorithms can make a guess that looks optimum at the time but becomes costly down the line and do not guarantee a globally optimum.

Dynamic programming, on the other hand, finds the optimal solution to subproblems and then makes an informed choice to combine the results of those subproblems to find the most optimum solution.

