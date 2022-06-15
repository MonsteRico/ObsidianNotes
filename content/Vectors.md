---
title: "Vectors"
tags:
  - Calc-2
  - Math
  - Vectors
---

# Vectors

Scalars: (numbers) 5, -13, $\pi$ etc

- have magnitude only
- no sense of directions
  Compare to _vectors_, for example, I am traveling at **65** mph **north**
- There's a sense of magnitude - 65 mph
- and a sense of direction - north

Mathematically, vectors are represented by arrows

![[Examples/Calc 2/Vector ex 1.png]]
written as vector $\vec{OP}$ , put the point you start at, then the point you end at, and put an arrow on top
vector $\vec{OP} = <1, 2> = 1\vec{i} + 2\vec{j}$
^ this is how far to move right, the other number is how far to move up
i indicates a vector in the x direction, j a vector in the y direction, and k (not here yet) in the z direction

in general, <destination x - starting x, destination y - starting y>

What about vector $\vec{PO}$

![[Examples/Calc 2/VEctor ex 2.png]]

$\vec{PO} = <-1, -2>$

Note: $\vec{PO} = -1 * \vec{OP}$
In general, multiplying a vector by -1 reverses its direction while keeping the magnitude the same

## Multiplying by scalars

very simple to do

$2 \vec{OP} = <2 * 1, 2 * 2> = <2,4>$

This changes the magnitude (length of the vector) by a factor equal to the scalar

$-3 \ \vec{OP}$ reverses OP's direction and lengthens it by a factor of 3

## Finding Magnitude

![[Examples/Calc 2/Vector ex 1.png]]

To find the magnitude (length) of vector OP, written as $|\vec{OP}|$

There's a right angle triangle in there! We know the base and the height, so the magnitude is

$|\vec{OP}| = \sqrt{(1)^{2} + (2)^{2}} = \sqrt{5}$

Generalized, if $\vec{u} = <a, b>$, then the magnitude is $|\vec{u}| = \sqrt{a^{2}+b^{2}}$

## Moving Vectors

Copies of the same vector at different locations are **equal**
![[Examples/Calc 2/Vectors 3.png]]
Each of these $\vec{v}$ is called a position vector
(gives the relative difference between start and end)

Even if a vector is moved, they are the same as long as they have the same magnitude and direction

Two Vectors are equal if they have the same magnitude and the same direction

## Vector Operations

### Adding and Subtracting vectors

Algebraically, very easy

$\vec{u} = < 1, 2> \ \ \  \vec{v} = <0,3>$
$\vec{u} + \vec{v} = <1+0, 2+3> = <1, 5>$
$\vec{u} - \vec{v} = <1-0, 2-3> = <1, -1>$

$2 \ \vec{u} - 3 \ \vec{v} = <2,4> - <0,9> = <2, -5>$

Graphically, things get more interesting

When adding, keep first vector the same and move the second vectors tail to the head of the first. Create a new vector from the tail of the first vector to the head of the second to get the final vector result.

![[Examples/Calc 2/Vector Ex 4.png]]
This is called the **Triangle Rule**

Another way called the **Parallelogram Rule**
It basically does the same thing, just looks a bit different.
![[Examples/Calc 2/Vectors Ex 5.png]]

Subtraction graphically looks like doing $\vec{u} + (-\vec{v})$
![[Examples/Calc 2/VEctors Ex 6.png]]

### Multiplying, just look at scalars above its that

## [[Dot Product]] and [[Cross Product]]

## Unit Vectors

These are vectors with a magnitude of 1

A unit vector parallel to $|\vec{PQ}|$ is $\frac{\vec{PQ}}{|\vec{PQ}|} = <\frac{3}{\sqrt{50}}, \frac{4}{\sqrt{50}}, \frac{5}{\sqrt{50}}>$
Another one is $-\frac{\vec{PQ}}{|\vec{PQ}|}$
![[Examples/Calc 2/Unit VEctors.png]]
