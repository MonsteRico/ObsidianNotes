---
title: "Root Test"
tags:
  - Calc-2
  - Math
  - Series
---

# Root Test

The root test is very similar to the [[Ratio Test]]

Given $\sum\limits_{k=1}^{\infty}a_{k}$, it converges absolutely if $\lim_{k\to\infty} \sqrt[k]{|a_{k}|} < 1$
It diverges if $\lim_{k\to\infty} \sqrt[k]{|a_{k}|} > 1$
The test is inconclusive if $\lim_{k\to\infty} \sqrt[k]{|a_{k}|} = 1$

Why?
$\lim_{k\to\infty} \sqrt[k]{|a_{k}|} = r$, then this means that as k -> infinity, $|a_{k}| \approx r^{k}$ which means $\sum\limits|a_{k}| = \sum\limits r^{k}$ which is a geometric series, and if $|r| < 1$ it will converge

The Root Test works the best when there is an exponent of k in $a_{k}$

![[Examples/Calc 2/Root Test Ex 1.png]]
