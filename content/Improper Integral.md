---
title: "Improper Integral"
tags:
  - Calc-2
  - Math
  - Integrals
---

# Improper Integrals

Improper Integrals let us find the area under an entire curve, or from a point to infinity.

$$\int_{a}^{\infty} \frac{1}{x} dx$$
These integrals are solved by replacing infinity with a $b$ or some other variable and then doing $$\lim_{b\to\infty} \int_{a}^{b} f(x) dx$$
Improper Integrals are [[Convergence and Divergence#In Improper Integrals|Convergent]] if they result in a number, they are [[Convergence and Divergence#In Improper Integrals|Divergent]] if they result in plus or minus infinity.

Improper integrals where $f(x) = \frac{1}{x^{p}}$ will converge if $p > 1$ and will diverge if $p \leq 1$

Another kind of improper integral is when the function becomes undefined along the integral bounds.
e.g. $$\int_{-2}^{3} \frac{1}{x^{4}} dx$$
In this case, split up the integral and do the limit as a variable approaches the spot where the function becomes undefined. For the above example,
$$\lim_{b\to0^{-}} \int_{-2}^{b} \frac{1}{x^{4}}dx + \lim_{a\to0^{+}}\int_{a}^{3} \frac{1}{x^{4}} dx$$
Solve both by finding the limit

Sometimes we can do a [[Comparison Tests|Comparison Test]] to quickly determine if an improper integral converges. They function the same as direct comparison tests for series, take a look at that page, except we compare improper integrals instead of series'.
