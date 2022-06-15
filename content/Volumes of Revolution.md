---
title: "Volumes of Revolution"
tags:
  - Calc-2
  - Math
  - Integrals
---

# Volumes of Revolution

A Volume of Revolution is created by rotating a curve around an axis from one point to another.
![[Examples/Calc 2/volumes of revolution disk.png]]

## Finding the Volume

### Disk/Washer Method

The disk washer method, pictured above, involves finding the volume of multiple small disks and then integrating to accumulate them.

Formula $$\int_{a}^{b}[\pi(outer\ curve)^{2} - \pi(inner\ curve)^{2}]dx$$
You can also integrate in y, just be careful that you are actually using disks/washers.

Importantly, **when using the disk/washer method, your rectangles should be _perpendicular_ to the axis of revolution**
![[Examples/Calc 2/volume of revolution disk 2.png]]
Another picture description

### Shell Method

In the Shell Method, you find the volume of many cylinders and integrate to accumulate those.

![[Examples/Calc 2/volume of revolution shell.png]]
Explanation

The important thing with the shell method **is that the rectangles end up _parallel_ to the axis of revolution**

Formula $$\int_{a}^{b}2\pi\ radius\ * [height\ or\ length\ of\ the\ rectangle]\ dx$$
the radius is the distance the rectangle is from the axis of revolution (usually ends up being just x)

## Surface Area of a Volume of Revolution

FORMULA: $$\int_{a}^{b} 2 \pi f(x) \sqrt{1+[f'(x)]^{2}}dx$$
It is nearly identical to the length of a curve formula

Process is same as every other type of integration, find surface area of a small strip, integrate to accumulate. Here's the drawn out version.
![[Examples/Calc 2/volume of revolution surface area.png]]
