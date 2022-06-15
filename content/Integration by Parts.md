---
title: "Integration by Parts"
tags:
  - Calc-2
  - Math
  - Integrals
---

# Integration by Parts

Integration using substitution is the chain rule in reverse.

Similarly, Integration by Parts is the product rule in reverse

We have two functions, u and v, both functions of x
The product rule of these two functions would give us $uv'+vu'$ , which can be rewritten in terms of integrals as $\int uv'dx + \int v u'dx$
These can be further simplified into $\int udv + \int vdu$. Through a bit of algebra we end up with the final formula,
$$\int udv = uv - \int vdu$$
We choose u within our integral based off the following acronym

## LIATE

L - logarithms
I - Inverse Trig Functions
A - Algebraic Functions
T - Trig functions
E - Exponential Functions

choosing u based off this will let us end up with an easier integral in the end.

Choose u based off of this, make the rest of the function dv. Then find du and v and plug everything into the equation above.

This rule can be violated, its just a rule of thumb but it usually works

## Example

$\int \ln(x) x\ dx$
since $\ln(x)$ is a logarithm, which is the highest on our list, we choose that as u

$u = \ln(x), dv = xdx$
$du = \frac{1}{x}dx, v = \frac{x^{2}}{2}$
don't bother including +C in the v term, since you'll add one in at the end anyways.

$\ln(x) \frac{x^{2}}{2} - \int \frac{x^{2}}{2} \frac{1}{x} dx$
$\ln(x) \frac{x^{2}}{2} - \frac{1}{2}\int x dx$
$\frac{1}{2}x^{2}\ln(x)- \frac{1}{4}x^{2}+C$

In a definite integral, the bounds of the integral remain the same, and don't forget to evaluate the uv part.
