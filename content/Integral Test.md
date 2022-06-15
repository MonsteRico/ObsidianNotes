---
title: "Integral Test"
tags:
  - Calc-2
  - Math
  - Series
---

# Integral Test

If we treat the partial sums from a series as points on a graph,

![[Examples/Calc 2/Integral Test Ex 1.png]]

Ignoring the first rectangle, we can write it as an integral.

$\sum\limits_{k=1}^{\infty} \frac{1}{k^{2}} \leq 1 + \int_{1}^{\infty} \frac{1}{x^{2}} \, dx$ (the 1 accounts for the first term/rectangle)

We could also use a different Riemann Sum

![[Examples/Calc 2/Integral Test Ex 2.png]]

If we combine these two we end up with,

$\int_{1}^{\infty} \frac{1}{x^{2}}\,dx \leq \sum\limits_{k=1}^{\infty} \frac{1}{k^{2}} \leq 1 + \int_{1}^{\infty} \frac{1}{x^{2}} \,dx$
If the [[Improper Integral|improper integral]] converges then the series is between two finite #'s, so the series must also converge. Otherwise the series diverges.

## Examples

![[Examples/Calc 2/Integral Test Ex 3.png]]![[Examples/Calc 2/Integral Test Ex 4.png]]
