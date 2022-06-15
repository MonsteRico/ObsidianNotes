---
title: "Convergence Tests"
tags:
  - Calc-2
  - Math
  - Series
---

# Convergence Tests

There are multiple tests we can do to test if an infinite [[Series|series]] [[Convergence and Divergence|converges]].

This page contains the quick guide to each test, each test has its own note going into more detail on how it works and with examples.

An important note, the starting index of a series does not affect convergence

$\sum\limits_{k=1}^{\infty} \frac{1}{k^{2}}$ converges, so does $\sum\limits_{k=29}^{\infty} \frac{1}{k^{2}}$
$\sum\limits_{k=1}^{\infty} \frac{1}{k}$ diverges, so does $\sum\limits_{k=1329}^{\infty} \frac{1}{k}$

## Geometric Series Convergence

**_Useful only for geometric series_**
A [[Geometric Series|geometric series]] converges if $|r| < 1$ in $\sum\limits_{k=1}^{\infty}ar^{k}$

## Divergence Test

**_This is the $0^{th}$ test, use this one first_**
[[Divergence Test]]

If $\sum\limits_{k=1}^{\infty}a_{k}$ converges, then $\lim_{k\to\infty} a_{k} = 0$
If $\lim_{k\to\infty} a_{k} \neq 0$, then the series diverges

This is a one way statement, if $\sum\limits_{k=1}^{\infty}a_{k}$ converges THEN the limit = 0. BUT if the limit = 0, there's still a chance the series could diverge

A better way of using this test is if the $\lim_{k\to\infty} a_{k} \neq 0$, then the series diverges. If it equals 0, the series might converge or diverge.

## Integral Test

**_Ask "is this easy to integrate"_**
[[Integral Test]]

$\sum\limits_{k=1}^{\infty} a(k)$ converges if $\int_{1}^{\infty} a(x) \,dx$ converges
$\sum\limits_{k=1}^{\infty} a(k)$ diverges if $\int_{1}^{\infty} a(x) \,dx$ diverges

## P-Series Test

#### $\sum\limits_{k=1}^{\infty} \frac{1}{k^{p}}$ converges if $p \geq 1$

(This is because the associated Integral Test converges if $p > 1$)

## Direct Comparison Test

**_Compare the series to a p-series or a geometric series_**
[[Comparison Tests]]

If $a_{k} \leq$ the terms of a convergent series, then the series converges
If $a_{k}\geq$ the terms of a divergent series then the series diverges

## Limit Comparison Test

**_Compare the series to a p-series or a geometric series_**
[[Comparison Tests]]

$\lim_{k\to\infty} \frac{a_{k}}{b_{k}} = c \geq 0$ then both series either converge or both diverge

## Alternating Series Test

**_Good only with Alternating Series_**
[[Alternating Series]]

$\sum\limits_{k=1}^{\infty}(-1)^{k}a_{k}$ converges IF
$\lim_{k\to\infty} a_{k}= 0$ AND $a_{k}$ is eventually non increasing

## Ratio Test

**_Very good first test to try, but it can't handle any kind of p-series_**
[[Ratio Test]]

$\lim_{k\to\infty} | \frac{a_{k+1}}{a_{k}} | < 1$, series converges absolutely (and therefore converges)
$\lim_{k\to\infty} | \frac{a_{k+1}}{a_{k}} | > 1$, series diverges
$\lim_{k\to\infty} | \frac{a_{k+1}}{a_{k}} | = 1$, test is inconclusive try another

## Root Test

**_Really only good to use when there is a k in the exponent_**
[[Root Test]]

$\lim_{k\to\infty} \sqrt[k]{|a_{k}|} < 1$ -> series is convergent
$\lim_{k\to\infty} \sqrt[k]{|a_{k}|} > 1$ -> series is divergent
$\lim_{k\to\infty} \sqrt[k]{|a_{k}|} = 1$ -> test is inconclusive
