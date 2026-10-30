---
created: 2026-10-27
updated: 2026-10-28
---
The **chain rule** gives the [[Derivative]] of a composition of [[Function|functions]].

**One variable**: if $y = f(u)$ and $u = g(x)$, then
$$\frac{dy}{dx} = \frac{dy}{du}\cdot\frac{du}{dx}$$
or equivalently $(f \circ g)'(x) = f'(g(x))\,g'(x)$.

**Several variables**: if $z = f(u_1, \dots, u_m)$ and each $u_j = g_j(x_1, \dots, x_n)$, then, using [[Partial Derivative|partial derivatives]],
$$\frac{\partial z}{\partial x_i} = \sum_{j=1}^{m} \frac{\partial z}{\partial u_j}\,\frac{\partial u_j}{\partial x_i}$$

For a composition of several functions, the derivative is the product of the derivatives of each step.