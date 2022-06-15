---
title: "Dot Product"
tags:
  - Calc-2
  - Math
  - Vectors
---

# Dot Products

Given 2 vectors, $\vec{u} = < u_{1}, u_{2}, u_{3}>$ and $\vec{v} = <v_{1}, v_{2}, v_{3}>$
the dot product is $\vec{u}\cdot\vec{v} = u_{1}v_{1}+u_{2}v_{2}+u_{3}v_{3}$

Dot Product is an operation on 2 vectors that results in a scalar, a single number.

Let $\vec{u} = <4, 1, -2>, \vec{v} = <3, 4, 5>$
Then $\vec{u}\cdot\vec{v} = 4\cdot3 + 4\cdot1+-2\cdot5=12+4+-10=6$

## Geometric Meaning

![[Examples/Calc 2/Dot Product 1.png]]

THEOREM: If $\vec{u}$ and $\vec{v}$ are nonzero vectors, then $\vec{u}\cdot\vec{v} = |\vec{u}||\vec{v}|cos\theta$
Where $0 \leq \theta \leq \pi$

We can use this to calculate the angle $\theta$ between $\vec{u}$ and $\vec{v}$

$$\cos^{-1}\left(\frac{\vec{u}\cdot\vec{v}}{|\vec{u}||\vec{v}|}\right)= \theta$$

## Orthogonal Projection

Two vectors are **Orthogonal** if and only if $\vec{u}\cdot\vec{v} = 0$
Notation: $\vec{u} \perp \vec{v}$
Note: In 2D and 3D, two non zero orthogonal vectors are perpendicular to each other
Orthogonal and Perpendicular are basically the same

The Orthogonal projection of $\vec{u}$ onto $\vec{v}$, denoted as $proj_{\vec{v}}(\vec{u})$ where $\vec{v} \neq 0$ is
$$proj_{\vec{v}}(\vec{u}) = |\vec{u}|\cos\theta(\frac{\vec{v}}{|\vec{v}|})$$
$|\vec{u}|\cos\theta$ represents the scalar length, and $\frac{\vec{v}}{|\vec{v}|}$ is the unit vector giving the direction

We can also use the formula $$proj_{\vec{v}}(\vec{u}) = (\frac{\vec{u}\cdot\vec{v}}{\vec{v}\cdot\vec{v}})\vec{v}$$
This formula is useful because we don't need to calculate $\theta$. It works because if you convert the dot products to the previous definition, things cancel out leaving the original formula.

## Applications of Dot Product

Dot Product can be used to find Work

Let a constant force $\vec{F}$ be applied to an object, producing a displacement $\vec{d}$. If the angle between $\vec{F}$ and $\vec{d}$ is $\theta$, then the Work done by the force is $$W = \vec{F}\cdot\vec{d}$$
The Force is in Newtons and the resulting scalar (Work) is in Joules

![[Examples/Calc 2/Work example.png]]
