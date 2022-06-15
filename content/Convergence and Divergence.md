---
title: "Convergence and Divergence"
aliases: [Convergence, Divergence, convergent, divergent]
tags:
  - Calc-2
  - Math
  - Series
  - Integrals
---

Convergence means the series or sequence or integral eventually approaches a finite number.

Divergence means the series or sequence or integral never approaches a finite number, it just continues to grow.

# In Sequences

A Sequence converges if its terms approach a finite number. What a sequence converges to (if anything) can be found by doing the limit $\lim_{n \to \infty} a_{n} = L$ (some number) where $a_n$ is the [[Sequences#Explicit Formula|explicit form]] of the sequence. For the series to converge, the limit has to equal some number. This number is known as the Limit of the Sequence.

A Sequence diverges if the limit $\lim_{n \to \infty} a_{n} = DNE$. This means the terms of the sequence never approach a finite number.

## Example

![[Examples/Calc 2/Sequences Ex 2.png]]

# In Series

A Series converges if it eventually reaches a finite sum. Another way of putting it is if the Sequence of the [[Series#Partial Sums|partial sums]] converges, then the series converges.

The limit as n approaches infinity of $S_n$ exists.
$$\lim_{n\to \infty} \frac{2^{n-1}}{2^{n}} = 1$$
This means no matter how many terms are added , the sum will never exceed 1 (the result of the limit above). Thus the series converges to 1.

### Absolute/Conditional Convergence

A series that is absolutely convergent is also convergent. If a series converges, but not absolutely, then it is conditionally convergent. Absolutely convergent means that the series converges when the absolute value of its terms are taken.
![[Examples/Calc 2/Absolutely Convergent.png]]

Why does absolute convergence imply convergence?

We know $-|a_{k}| \leq a_{k}\leq |a_{k}|$ If you add $|a_k|$ to all parts you end up with
$$0 \leq a_{k}+ |a_{k}| \leq 2|a_{k}|$$
If you sum those for all k you get the following,
$$0 \leq \sum\limits(a_{k}) + \sum\limits(|a_{k}|) \leq 2\sum\limits(|a_k|)$$
This means that if $\sum\limits |a_{k}|$ converges, then the series $\sum\limits a_{k}$ is trapped between 0 (a finite number) and another finite number and therefore also must converge.

A series that is conditionally convergent sums up to a different number if you rearrange the terms in the series. An absolutely convergent series will always add up to the same sum.

# In Improper Integrals

If the improper integral has a finite answer, it is convergent. Otherwise it is divergent.

![[Examples/Calc 2/Converging Improper Integral.png]]
