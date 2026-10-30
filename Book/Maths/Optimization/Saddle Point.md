---
created: 2026-10-28
updated: 2026-10-28
---
A **saddle point** of a differentiable function $f : \mathbb{R}^n \to \mathbb{R}$ is a [[Critical Point]] $\mathbf{x}^*$ that is not a local [[Extremum]].

**Conditions**
- $\nabla f(\mathbf{x}^*) = 0$.
- In every neighborhood of $\mathbf{x}^*$, there are points $\mathbf{x}$ with $f(\mathbf{x}) > f(\mathbf{x}^*)$ and points with $f(\mathbf{x}) < f(\mathbf{x}^*)$.

**Characterization** (twice-differentiable $f$)
- If the [[Hessian]] at $\mathbf{x}^*$ has [[Eigenvalues]] of both signs (indefinite), $\mathbf{x}^*$ is a saddle point.
- If the Hessian is only semidefinite (some eigenvalue is $0$), the test is inconclusive.

**Example**
- $f(x, y) = x^2 - y^2$ at the origin: a minimum along the $x$-axis and a maximum along the $y$-axis. The Hessian is $\mathrm{diag}(2, -2)$.

**Analogue in one variable**
- $f(x) = x^3$ at $0$: critical point that is neither a minimum nor a maximum.