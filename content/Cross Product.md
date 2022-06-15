---
title: "Cross Product"
tags:
  - Calc-2
  - Math
  - Vectors
---

# Cross Product

Cross Product is another operation that can be done on two vectors. The result of doing the cross product is another vector

The magnitude of the cross product is given by
$$|\vec{u} \times\vec{v}|= |\vec{u}||\vec{v}|\sin\theta$$
The direction is given by the **Right Hand Rule**
For $\vec{u}\times\vec{v}$ , curl the first vector into the second using the fingers of your right hand. The direction of your thumb is the direction of $\vec{u}\times\vec{v}$
**ALWAYS USE THE RIGHT HAND FOR THIS**

![[Examples/Calc 2/Cross Product 1.png]]
In this case, $\vec{u}\times\vec{v}$ is coming out of the screen, since your thumb would be pointing straight up.
$\vec{v}\times\vec{u}$ has your thumb pointing down, so $\vec{v}\times\vec{u}$ points into the screen. Both cross products will have the same magnitude, but opposite directions

$\vec{u}\times\vec{v} = -(\vec{v}\times\vec{u})$ Order matters in cross products

Another note, $\vec{u}\times\vec{v}$ and $\vec{v}\times\vec{u}$ are perpendicular/orthogonal to both $\vec{v}$ and $\vec{u}$

The cross product of two parallel vectors is the 0 vector. (<0, 0, 0> or <0,0>)

The positions of the XYZ axes obey the right hand rule.
![[Examples/Calc 2/XYZ cross product.png]]

## Finding the Cross Product

To find the cross product of two vectors, we use determinants.
Quick reminder on determinants:
![[Examples/Calc 2/cross product determinant.png]]

Here's how we apply it using vectors to find the cross product.
![[Examples/Calc 2/Cross Product Finding.png]]

**NOTE THAT FOR THE j PART WE ALWAYS PUT A NEGATIVE IN FRONT**

After setting up the determinants like this, we then solve the determinants.
So, $\vec{u}\times\vec{v}$ using the above vectors is
$\vec{i}(1*1-0*1)-\vec{j}(2*1-5*1)+\vec{k}(2*0-5*1) = \vec{i}+3\vec{j}-5\vec{k} = <1,3,-5>$

$\vec{v}\times\vec{u} = <-1,-3,5>$ , which can be found by flipping the signs of $\vec{u}\times\vec{v}$ since its just the opposite direction

You can check if its perpendicular by taking the [[Dot Product]] of the Cross Product and one of its parts
$(\vec{v}\times\vec{u})\cdot\vec{u}=0$
and so on

## Applications of Cross Product

### Area of Parallelogram

$|\vec{u}\times\vec{v}|$ is the area of the parallelogram with adjacent sides $\vec{u}$ and $\vec{v}$
![[Examples/Calc 2/Area of paralellogram.png]]

### Collinear and coplanar vectors

If vectors $\vec{AC}$ and $\vec{AB}$ are on the same line (collinear) then $\vec{AB}\times\vec{AC}=\vec{0}$ because $\sin 0 = 0$

If A,B,C, and D are all on the same plane (coplanar), then $\vec{AB}\times\vec{AC}$ and $\vec{AC}\times\vec{AB}$ are perpendicular to any vector on the plane,
so $(\vec{AB}\times\vec{AC})\cdot\vec{AD}=0$
and $(\vec{AC}\times\vec{AB})\cdot\vec{AD}=0$

### Torque (or moment)

![[Examples/Calc 2/cross product torque.png]]

The Torque about the Point O is $|\vec{OP}\times\vec{F}|$

### Magnetic Force

A particle with charge $q$ is moving with velocity $\vec{v}$ through a magnetic field $\vec{B}$
The Force due to the magnetic field on the particle is found by
$$\vec{F}=q(\vec{v}\times\vec{B})$$
