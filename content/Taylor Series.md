---
title: "Taylor Series"
tags:
  - Calc-2
  - Math
  - Series
---

# Taylor Series

A Taylor Series is a type of [[Power Series]]

What are the $C_k$'s of the Taylor Series?

The idea with a Taylor series is that it should behave similarly to it's corresponding f(x)
=> The way we do this is we match all the derivatives at x = a

The coefficients of the Taylor Series look like $C_{k}= \frac{f^{k}(a)}{k!}$

Taylor Series of f(x) at x=a $$\sum\limits_{k=0}^{\infty} \frac{f^{(k)}(a)}{k!} (x-a)^{k} = f(a) + f'(a)(x-a) +\frac{f''(a)}{2!}(x-a)^{2}+\frac{f'''(a)}{3!}(x-a)^3+...$$
We have seen part of this before, if you chop the series off after the first derivative you get
$$f(x) = f(a)+f'(a)(x-a)$$
This is the Linear Approximation of f(x) near f(a)

So think of the Taylor Series as an extension of linear approximation. We use more derivatives to better capture the shape and behavior of f(x)

## Example Finding Taylor Series

![[Examples/Calc 2/Finding taylor series.png]]

## Taylor Polynomials

If you cut off after the kth degree term, you get what's known as the kth order Taylor Polynomial ($P_{k}$)

In the above example, the Taylor Polynomials are as follows,
$P_{0}= 1$
$P_{1}=1+x$
$P_{2}= 1+x+\frac{x^{2}}{2}$
$P_{3}=1+x+ \frac{x^{2}}{2} + \frac{x^{3}}{3}$
.
.
.

## Taylor Remainder Theorem

The Taylor Remainder is everything that we cut off from the series to make the Taylor Polynomial
In general $f(x)= P_{n}(x) + R_{n}(x)$

For example, $P_{2} = f(a) + f'(a)(x-a) + \frac{f''(a)}{2!}(x-a)^{2}$
The remainder of it (the second Taylor Remainder) is $R_{2} = \frac{f'''(a)}{3!}(x-a)^{3} + \frac{f^{(4)}(a)}{4!}(x-a)^{4}+...$
The remainder is an infinite series which converges to something given by Taylors Remainder Theorem

Taylor Remainder Theorem says

$R_{n}$ converges to $$R_{n}=\frac{f^{(n+1)}(c)}{(n+1)!}(x-a)^{n+1}$$
where $c$ is somewhere between $a$ and $x$

$c$ is usually very hard to find, so instead we usually just find the maximum value of the n+1'th derivative on the interval between x and a, calling that M. (Make sure to include the endpoints!)

We can use the remainder $R_{n}$ to estimate how much error is in the approximation of f(x)

$$|f(x) - P_{n}(x) | = |R_{n}(x)| = |\frac{f^{(n+1)}(c)}{(n+1)!}(x-a)^{n+1}|$$ so long as $a \leq c \leq x$

### Examples can be found [Day 28 of Calc 2](onenote:https://d.docs.live.net/f392cf082438fd86/Documents/My%20Notebook/CALC%202.one#section-id={0DEC288B-763B-483D-97EA-B892C3EC6B0B}&page-id={289F5485-A03F-4892-8A56-79F63743E4B8}&end) 

## Maclaurin Series

A Maclaurin Series is literally just a Taylor Series where $a = 0$. That's it.

We use Maclaurin Series to find other Power Series' like how we used $\frac{1}{1-x}$ in [[Power Series|these examples]]

![[Examples/Calc 2/Common Maclaurin Series.png]]