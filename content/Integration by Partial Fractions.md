---
title: "Integration by Partial Fractions"
tags:
  - Calc-2
  - Math
  - Integrals
---

# Partial Fractions

We know the formula $$\int \frac{1}{ax+b}dx = \frac{1}{a}\ln|ax+b| +C$$
is true, so if we can convert an integral into the form of multiple of those types of fractions, we can easily integrate it.

# Partial Fraction Expansion

**FOR PARTIAL FRACTION EXPANSION TO WORK THE NUMERATOR _MUST_ HAVE A LOWER DEGREE THAN THE DENOMINATOR**

If it does not, do long division so that it does.

## Case 1: Denominator is a product of DISTINCT LINEAR factors

- Distinct means they aren't repeating
- Linear means they are of first degree

$$\frac{x-8}{x^{2}-7x+10}= \frac{x-8}{(x-5)(x-2)} = \frac{A}{x-5} + \frac{B}{x-2}$$
this is similar to how $\frac{1}{6}= \frac{A}{3}+ \frac{B}{2}$
all we have to do is find A and B.

Do this by multiplying both sides of the equation by the denominator and solving the resulting system of equations for A and B

## Case 2: Denominator is a product of linear factors, some of which are repeated

$$\frac{10}{x^{2}(5-2x)}= \frac{10}{(x)(x)(5-2x)}$$
In this case we do $$\frac{10}{(x)(x)(5-2x)}= \frac{A}{x} + \frac{B}{x^{2}} + \frac{C}{5-2x}$$
process for solving is the exact same

## Case 3: Denominator contains distinct irreducible quadratics

You should start to notice a pattern, which makes these pretty easy
$$\frac{2x^{2}-x+4}{x^{3}+4x} = \frac{2x^{2}-x+4}{x(x^{2}+4)} = \frac{A}{x} + \frac{Bx+C}{x^{2}+4}$$
Solve the exact same ways

## Case 4: Repeated Irreducible Quadratics

You handle these just like handling repeated linear factors, except the numerator is itself a linear term.

$$\frac{1}{x(x^{2}+1)^{2}} = \frac{A}{x}+ \frac{Bx+C}{x^{2}+1}+ \frac{Dx+E}{(x^{2}+1)^{2}}$$
Solve same way

## Example Combining all of the things

$$\frac{2x^{3}+5x-10}{x^{2}(x-3)(x^{2}+1)^{3}} = \frac{A}{x-3} + \frac{B}{x} + \frac{C}{x^{2}}+ \frac{Dx+E}{x^{2}+1} + \frac{Fx+G}{(x^{2}+1)^{2}}+ \frac{Hx+I}{(x^{2}+1)^{3}}$$
