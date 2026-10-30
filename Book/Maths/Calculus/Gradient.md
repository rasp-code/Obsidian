---
created: 2026-10-27
updated: 2026-10-28
---
The **gradient** of a differentiable scalar function $f : \mathbb{R}^n \to \mathbb{R}$ is the [[Vector]] of its [[Partial Derivative|partial derivatives]]:

$$\nabla f(\mathbf{x}) = \left(\frac{\partial f}{\partial x_1}, \dots, \frac{\partial f}{\partial x_n}\right)^\top$$

**Properties**
- $\nabla f(\mathbf{x})$ points in the direction of steepest increase of $f$ at $\mathbf{x}$; $-\nabla f(\mathbf{x})$ points in the direction of steepest decrease.
- $\|\nabla f(\mathbf{x})\|$ is the rate of increase of $f$ in that direction.
- It is orthogonal to the level sets of $f$.
- [[Directional Derivative]] along a unit vector $\mathbf{u}$: $D_{\mathbf{u}} f(\mathbf{x}) = \nabla f(\mathbf{x}) \cdot \mathbf{u}$.
- If $\nabla f(\mathbf{x}) = 0$, $\mathbf{x}$ is a critical point of $f$.