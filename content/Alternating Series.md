---
title: "Alternating Series"
tags:
  - Calc-2
  - Math
  - Series
---

# Alternating Series

An Alternating Series is a type of [[Series|series]] where each term has a different sign

$$\sum\limits_{k=1}^{\infty} (-1)^{k+1} \frac{1}{k} = 1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \frac{1}{5} - ...$$

The above series is known as the Alternating Harmonic Series (the one that doesn't flip terms is the Harmonic Series)

The $(-1)^{k+1}$ changes the sign of each term

In General, alternating series usually look like

$$\sum\limits_{k=1}^{\infty}(-1)^{k+1}a_{k}$$
or
$$\sum\limits_{k=1}^{\infty} (-1)^{k}a_{k}$$
where $a_{k}\geq 0$

An Alternating Series converges if the following conditions are met

1. The magnitude of each term is eventually _non increasing_ $a_{k+1} \leq a_k$ for $k \geq$ some number
2. $\lim_{k\to\infty} a_{k} = 0$ (basically the [[Divergence Test|divergence test]])

These two things together are called the Alternating Series Test

### Why?

Look at $\sum\limits_{k=1}^{\infty} (-1)^{k+1} \frac{1}{k} = 1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \frac{1}{5} - ...$
It's easy to see that the limit = 0 and that $\frac{1}{k}$ is non increasing for $k \geq 1$ so this series converges
If you look at the series' partial sums, you see that they get closer and closer to about 0.7

![[Examples/Calc 2/Alternating Series Ex 1.png]]

## Example

![[Examples/Calc 2/Alternating Ex 2.png]]

## Estimating the sum of a convergent series

We can estimate the sum of a convergent alternating series to be within any accuracy we want

Look at $\sum\limits_{k=1}^{\infty}(-1)^{k+1}a_{k}$, assume it converges
![[Examples/Calc 2/Alternating Ex 3.png]]

Note: the true sum is always between $S_{k+1}$ and $S_k$
$$S_{k}\leq S \leq S_{k+1}$$ where S is the true sum

If you subtract $S_k$ and take the absolute value, you end up with
$$0 \leq |S - S_{k}| \leq |S_{k+1} - S_{k}|$$ $S_{k+1}-S_{k} = a_{k}$
and $S-S_{k}$ is the remainder after the kth partial sum, $R_{k}$ this is how far the partial sum $S_{k}$ is from the true sum

So, $|S-S_{k}| \leq a_{k+1}$
the error of the kth partial sum from the true sum is no bigger than the magnitude of the next term

![[Examples/Calc 2/Alternating Ex 4.png]]
