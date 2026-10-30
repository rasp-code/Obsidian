---
created: 2026-10-27
updated: 2026-10-28
---
A set $C$ is **convex** if the segment between any two of its points stays in $C$.

A function $f : C \to \mathbb{R}$ defined on a convex set is **convex** if for all $x, y \in C$ and $\lambda \in [0, 1]$:

$$f(\lambda x + (1-\lambda)y) \leq \lambda f(x) + (1-\lambda) f(y)$$

Geometrically, the graph of $f$ lies below any chord joining two of its points. $f$ is **strictly convex** if the inequality is strict for $x \neq y$ and $\lambda \in (0,1)$. $f$ is **concave** if $-f$ is convex.

**Characterizations** (differentiable $f$)
- First order: $f(y) \geq f(x) + \nabla f(x)^\top (y - x)$ for all $x, y$, i.e. $f$ lies above its tangent hyperplanes (see [[Gradient]]).
- Second order (one variable): $f''(x) \geq 0$ everywhere (see [[Derivative]]). In several variables, the Hessian is [[Positive Definite Matrix|positive semidefinite]] everywhere.

**Consequences for minimization**
- Every [[Local Minimum]] of a convex function is a [[Global Minimum]].
- A strictly convex function has at most one global minimum.