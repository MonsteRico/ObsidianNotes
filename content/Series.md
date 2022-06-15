---
title: "Series"
tags:
  - Calc-2
  - Math
  - Series
---

# Series

A **series** is the sum of the numbers in a [[Sequences|sequence]].
A series looks like this
![[Examples/Calc 2/Series Structure.png]]
[[Sequences#Explicit Formula|Explicit Formula]]

### $\sum\limits_{n=1}^{k}n = 1 + 2 + 3 + 4 + 5 + ... + k$ This series is **finite** it ends at a finite $k$ value.

### $\sum\limits_{n=1}^{\infty}n = 1 + 2 + 3 + 4 + 5 + ...$ This is an **infinite** series, the series never ends.

### $\sum\limits_{n=1}^{\infty} \frac{1}{2^{n}}= \frac{1}{2}+ \frac{1}{4} + \frac{1}{8} + \frac{1}{16} + \frac{1}{32} + ...$

## Partial Sums

The _sum of the first n terms_ is called the _nth partial sum_.

Parital sums of $\sum\limits_{n=1}^{\infty} \frac{1}{2^{n}}$
$S_{1}= \frac{1}{2}$ - first partial sum
$S_{2} = \frac{3}{4}$ - Sum of the first 2 terms
$S_{3}= \frac{1}{2} + \frac{1}{4} + \frac{1}{8} = \frac{7}{8}$
$S_{4}= \frac{1}{2} + \frac{1}{4} + \frac{1}{8} + \frac{1}{16} = \frac{15}{16}$
.
.
.
$s_{10} = ... = \frac{1023}{1024}$
Note the trend: $S_{n}= \frac{2^{n-1}}{2^{n}}$ - this is the nth partial sum of the series

The limit as n approaches infinity of $S_n$ exists.
$$\lim_{n\to \infty} \frac{2^{n-1}}{2^{n}} = 1$$
This means no matter how many terms are added , the sum will never exceed 1 (the result of the limit above). When the series has a sum we say the series [[Convergence and Divergence|converges]] or is convergent.

Another way to state it: the series [[Convergence and Divergence|converges]] if the sequence of its partial sums is convergent.
=> We want $\{S_{1}, S_{2}, S_{3}, S_{4}, ... \}$ to converge

An example of a [[Convergence and Divergence|divergent]] series:
$$\sum\limits_{n=1}^{\infty}cos(n \pi) = -1 + 1 + -1 + 1 + -1 +... = \sum\limits_{n=1}^{\infty}(-1)^{n}$$ $S_{1}= -1$ The [[Sequences|sequence]] of partial sums is {-1 ,0, -1, 0, -1, ....}.  
$S_{2}= 0$ This sequence has no limit, the partial sums don't approach
$S_{3}= -1$ a finite number. So this series [[Convergence and Divergence|diverges]].
$S_{4}= 0$
$S_{5} = -1$
.
.
.

## Ways to test if a series converges [[Convergence Tests]]

## Types of Series'

[[Geometric Series]]

[[Alternating Series]]

[[Telescoping Series]]
