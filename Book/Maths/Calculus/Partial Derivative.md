---
created: 2026-10-27
updated: 2026-10-28
---
The **partial derivative** of a function $f(x_1, \dots, x_n)$ with respect to $x_i$ is the [[Derivative]] of $f$ with respect to $x_i$, all other variables being held constant:

$$\frac{\partial f}{\partial x_i}(\mathbf{x}) = \lim_{h \to 0} \frac{f(x_1, \dots, x_i + h, \dots, x_n) - f(\mathbf{x})}{h}$$

It measures the rate of change of $f$ along the axis of $x_i$, and is the [[Directional Derivative]] along the coordinate axis $\mathbf{e}_i$.

**Example**: for $f(x, y) = x^2 y + 3y$, we have $\dfrac{\partial f}{\partial x} = 2xy$ and $\dfrac{\partial f}{\partial y} = x^2 + 3$.

**Second-order partial derivatives**: $\dfrac{\partial^2 f}{\partial x_i \partial x_j}$. If these are continuous, the order of differentiation does not matter (Schwarz's theorem).