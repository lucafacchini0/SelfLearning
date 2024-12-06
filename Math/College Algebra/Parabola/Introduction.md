
A **parabola** is a U-shaped curve that can open upward, downward, left, or right. It is the graph of a quadratic function. Parabolas have properties such as a vertex, axis of symmetry, focus, and directrix

### Standard Equation of a Parabola

The general form of the equation of a parabola is:

$$
y = ax^2 + bx + c
$$

```functionplot
---
title: 
xLabel: 
yLabel: 
bounds: [-10,10,-10,10]
disableZoom: true
grid: true
---
y = x^2
```

where:
- $a$, $b$, and $c$ are constants. 
- $a$ controls the direction and width of the parabola:
  - If $a > 0$, the parabola opens **upwards**.
  - If $a < 0$, the parabola opens **downwards**.
- The shape of the parabola also depends on the value of $a$:
  - Larger values of $|a|$ result in a **narrower** parabola.
  - Smaller values of $|a|$ (closer to zero) make the parabola **wider**.

$a=0.5$

```functionplot
---
title: 
xLabel: 
yLabel: 
bounds: [-10,10,-10,10]
disableZoom: false
grid: true
---
y = 0.1x^2
```

$a=10$

```functionplot
---
title: 
xLabel: 
yLabel: 
bounds: [-10,10,-10,10]
disableZoom: false
grid: true
---
y = 10x^2
```

### Vertex Form of a Parabola

The vertex form of a parabola provides a more intuitive understanding of the curve, highlighting the **vertex** directly:

$$
y = a(x - h)^2 + k
$$

where:
- $(h, k)$ is the **vertex** of the parabola. This is the point where the curve reaches its minimum (if $a > 0$) or maximum (if $a < 0$).

### Finding the Vertex from Standard Form

To convert a parabola from the standard form $y = ax^2 + bx + c$ to vertex form, we can complete the square. However, we can also find the vertex directly from the coefficients in the standard form.

The x-coordinate of the vertex is given by the formula:

$$
x_{v} = -\frac{b}{2a}
$$

To find the corresponding y-coordinate $k$, substitute $h$ back into the original equation:

$$
y_{v} = a(h)^2 + b(h) + c
$$
$$
y_{v}= -\frac{\Delta}{4a}
$$


Thus, the vertex of the parabola is at $(h, k)$.

### Axis of Symmetry

The **axis of symmetry** is a vertical line that passes through the vertex, dividing the parabola into two symmetric halves. The equation of the axis of symmetry is:

$$
x = h
$$
$y = 5(x - 1)^2 + 5$
$V = (1, 5)$

```functionplot
---
title: 
xLabel: 
yLabel: 
bounds: [-10,10,-10,10]
disableZoom: false
grid: true
---
y = 5(x - 1)^2 + 5

```



### Focus and Directrix

The **focus** and **directrix** are geometric features of a parabola that describe its reflective properties. The focus is a point inside the parabola, and the directrix is a line outside the parabola. The defining property of a parabola is that any point on the curve is equidistant from the focus and the directrix.

- The **focus** is located a distance of $\frac{1}{4a}$ from the vertex along the axis of symmetry.
- The **directrix** is a line that is also $\frac{1}{4a}$ away from the vertex, but it lies on the opposite side of the vertex relative to the focus.

For a parabola in the form $y = a(x - h)^2 + k$:
- If the parabola opens **upward** ($a > 0$), the focus is at the point $(h, k + \frac{1}{4a})$, and the directrix is the line $y = k - \frac{1}{4a}$.
- If the parabola opens **downward** ($a < 0$), the focus is at the point $(h, k - \frac{1}{4a})$, and the directrix is the line $y = k + \frac{1}{4a}$.

For a parabola in the form $x = a(y - k)^2 + h$ (a horizontally opening parabola):
- If the parabola opens **to the right** ($a > 0$), the focus is at the point $(h + \frac{1}{4a}, k)$, and the directrix is the line $x = h - \frac{1}{4a}$.
- If the parabola opens **to the left** ($a < 0$), the focus is at the point $(h - \frac{1}{4a}, k)$, and the directrix is the line $x = h + \frac{1}{4a}$.

### Equation of a Parabola with Focus and Directrix

Given a parabola with focus $(h, k + \frac{1}{4a})$ (for an upward-opening parabola), the equation of the parabola can be derived using the geometric definition:

$$
\text{Distance to focus} = \text{Distance to directrix}
$$

This gives the standard form for vertical parabolas:

$$
y = a(x - h)^2 + k
$$

For horizontal parabolas, we would use a similar reasoning and the equation would take the form:

$$
x = a(y - k)^2 + h
$$

### Parabolas Opening Left or Right

For parabolas that open **left** or **right**, the equation is:

$$
x = a(y - k)^2 + h
$$

In this case:
- $(h, k)$ is the **vertex**.
- The **focus** has coordinates $(h + \frac{1}{4a}, k)$ if the parabola opens to the right, or $(h - \frac{1}{4a}, k)$ if it opens to the left.
- The **directrix** is the vertical line $x = h - \frac{1}{4a}$ for a right-opening parabola, or $x = h + \frac{1}{4a}$ for a left-opening parabola.

### Latus Rectum

The **latus rectum** is a line segment that passes through the focus of the parabola and is perpendicular to the axis of symmetry. The length of the latus rectum is given by:

$$
\text{Length of latus rectum} = \frac{1}{|a|}
$$

This is the distance between two points on the parabola that are both equidistant from the focus

