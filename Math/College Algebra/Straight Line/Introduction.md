
A straight line is the representation of infinite points in the Cartesian Plane. It's described with the following formula:
$$ y = mx + b $$

where:
- **m** is the slope, or the inclination of the line. 
	- m = 1: the inclination is 45 degrees
	- m < 1: the inclination is less than 45 degrees
	- m > 1: the inclination is higher than 45 degrees
	- m = 0: no inclination (basically, y = b, a perfectly horizontal line)
- **b** is the intersects, the point where the straight line intersects y (or x, for a x function) 


_This is a straight line given by the function_

$$ y = 2x + 6 $$

```functionplot
---
title: Straight Line
xLabel: 
yLabel: 
bounds: [-10,10,-10,10]
disableZoom: true
grid: true
---
y = 2x + 6
```
As you can see, the slope is equal to two, in fact, the line is "more inclined" than 45 degrees. Over that, the intersect is 6, and in fact, the y axis is intersected at point 6.

## Distance between two points

Consider two points that are sharing the same points in the X axis. If they are sharing the same point on the X axis, it's really easy: You just have to subtract the first Y with the second Y to find the distance.

$$ A(1, 4) B(1,3)$$
$$ d\overline{AB} = | (y_{b} - y_{a}) | $$

The same applies if they have the same y.

$$A(4,6)B(2,6)$$
$$d\overline{AB} = |x_{b} - x_{a}|$$
If both x and y differ, it's a bit different, because you would have to apply the "Teorema di Pitagora", considering the sides as the difference between the two points.

$$ A(3, 5)B(-3, 9) $$

Applying the formula
$$ \sqrt{ a^{2} + b^{2} } = c $$
$$\sqrt{ (x_{b} - x_{a}^{2}) + (y_{b} - y_{a})^{2} } = \overline{BA}$$
$$\sqrt{ (-3-3)^{2} + (9-5)^{2} } = \overline{AB}$$
$$ \sqrt{ 36 + 16 }  = \overline{AB} \implies \overline{AB} = \sqrt{ 52 }$$ 
## The slope

$$ m = \frac{\Delta y}{\Delta x} = \frac{x_{b} - x_{a}}{y_{b} - y_{a}}$$
- If two straight lines have the same slope, they're parallel.
- If the slope of two straight line, multiplied, gives -1 as result, they're perpendicular. 

## The intersect

First thing, you should calculate the slope. After having gotten the slope, you can substitute everything in your equation to find the intersect. Let's have an example

You are given two points
$$A(4,5)B(9,11)$$
Find the equation for the straight line.

1. Find the slope $$ m = \frac{\Delta y}{\Delta x} = \frac{y_{b} - y_{a}}{x_{b} - x_{a}} = \frac{5}{6}$$
2. Substitute with the one initial point and the slope 
 $$ y = mx + b \implies y = \frac{5}{6}x + b \implies 5 = \frac{5}{6}\cdot 4 + b $$
 3. Substitute to find the intersect

$$ -b = \frac{5}{4}\cdot 4 - 5 \implies b = -\frac{5}{6} \cdot 4 + 5 $$

## Point-Slope formula

For more professional context, if you can calculate the slope, it's better to use the following formula

$$y - y_{0} = m(x - x_{0}) $$
Substitute the slope with your result and y0 and x0 with a point of your straight line to find the final equation of the straight line


 