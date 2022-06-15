---
title: "Geometric Series"
tags:
  - Calc-2
  - Math
  - Series
---

# Geometric Series

A Geometric Series is a type of Infinite [[Series]]
In a Geometric Series, there is a consistent ratio between consecutive terms.
For example
$\frac{1}{4}  + \frac{1}{12} + \frac{1}{36} + \frac{1}{108} ...$
these can be written as $a+ar+ar^{2}+ar^{3}+...= \sum\limits_{k=0}^{\infty}ar^{k}$
However, if k starts at 1, then it needs to be $\sum\limits_{k=1}^{\infty}ar^{k-1}$

## Partial Sum of Geometric Series

To find the nth partial sum of a geometric series, you add up the terms from k=0 to k-1

$S_{k}= a + a+r + a+r^{2}+...+ar^{k-1}$

Manipulating this formula by multiplying it by r we get another formula,

$r*S_{k}= ar + ar^{2}+ar^{3}+... +ar^{k}$

Subtracting the second from the first results in this

$S_{k}- rS_{k}= a-ar^k$
$S_{k}(1-r) = a-ar^{k}$
$S_{k}= \frac{a-ar^{k}}{1-r}$

Another way of writing the formula:

# $S_{k}= \frac{first term}{1-r}$

This formula gives the kth partial sum of a geometric series with common ratio r

Example
![[Examples/Calc 2/Geo Series Ex 1.png]]

$\frac{1}{4}+ \frac{1}{12}+ \frac{1}{36}+ ... = \sum\limits_{k=0}^{\infty}ar^{k} = \sum\limits_{k=0}^{\infty} \frac{1}{4} \frac{1}{3}^k$
$a = \frac{1}{4}$, $r = \frac{1}{3}$

## Convergence of Infinite Geometric Series

What if we didn't stop and continued adding? Would the series always [[Convergence and Divergence|converge]]? If so what would its sum be?

$\lim_{k\to\infty}S_{k} = \lim_{k\to\infty} \frac{a(1-r^{k})}{1-r}$ for this limit to exist, the limit as k approaches infinity of $r^k$ has to be finite.
If |r| < 1, the limit = 0. From this we get

An Infinite Geometric Series converges if the $|r| < 1$ . A finite series will always converge.

Example
![[Examples/Calc 2/Geo Series Ex 2.png]]

## Using Geometric Series to rewrite decimals as fractions

![[Examples/Calc 2/Geo Series Ex 3.png]]
