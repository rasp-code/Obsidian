---
created: 2026-10-28
updated: 2026-10-28
---
The **directional derivative** of a [[Function]] $f : \mathbb{R}^n \to \mathbb{R}$ at a point $\mathbf{x}$ along a unit [[Vector]] $\mathbf{u}$ is the rate of change of $f$ at $\mathbf{x}$ in the direction $\mathbf{u}$:

$$D_{\mathbf{u}} f(\mathbf{x}) = \lim_{t \to 0} \frac{f(\mathbf{x} + t\mathbf{u}) - f(\mathbf{x})}{t}$$

Equivalently, $D_{\mathbf{u}} f(\mathbf{x}) = g'(0)$ for $g(t) = f(\mathbf{x} + t\mathbf{u})$, a function of one variable (see [[Derivative]], [[Limit]]).

**Conditions**
- $\mathbf{u}$ has [[Norm]] $1$.
- The limit exists.

**Properties**
- It exists along some directions even if $f$ is not differentiable at $\mathbf{x}$.
- Along the coordinate axes, it gives the partial derivatives: $D_{\mathbf{e}_i} f = \partial f / \partial x_i$.
- If $f$ is differentiable at $\mathbf{x}$, then $D_{\mathbf{u}} f(\mathbf{x}) = \nabla f(\mathbf{x}) \cdot \mathbf{u}$, where $\nabla f$ is the gradient, so $D_{\mathbf{u}} f$ is linear in $\mathbf{u}$.
- $D_{-\mathbf{u}} f(\mathbf{x}) = -D_{\mathbf{u}} f(\mathbf{x})$.