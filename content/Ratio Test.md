---
title: "Ratio Test"
tags:
  - Calc-2
  - Math
  - Series
---

# Ratio Test

Given $\sum\limits_{k=1}^{\infty}a_k$ the series will converge absolutely (and therefore converge) if $lim_{k\to\infty} |\frac{a_{k+1}}{a_{k}}| <1$
The series diverges if $lim_{k\to\infty} |\frac{a_{k+1}}{a_{k}}| > 1$
The test is inconclusive if $lim_{k\to\infty} |\frac{a_{k+1}}{a_{k}}| = 1$

Why? If $lim_{k\to\infty} |\frac{a_{k+1}}{a_{k}}| = r$ , then this means that as k becomes large, $|a_{k+1}| \approx r|a_{k}|$ which means that each term is r times the previous one, behaving like a [[Geometric Series|geometric series]]. And a geometric series converges for |r| < 1

## The process

replace all the k's in the original $a_k$ with (k+1) and divide it by the original. Take the limit as k approaches infinity and the absolute value.
Often you will end up multiplying by the reciprocal of the bottom and doing a lot of canceling out

## Examples

![[Examples/Calc 2/Ratio Test Ex 1.png]]

The ratio test is generally bad with things that look like p-series, in those cases its better to use the p-series test or a [[Comparison Tests|comparison test]]
