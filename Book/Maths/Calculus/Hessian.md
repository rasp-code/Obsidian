---
created: 2026-10-27
updated: 2026-10-28
---
The **Hessian** of a twice-differentiable scalar function $f : \mathbb{R}^n \to \mathbb{R}$ is the square [[Matrix]] of its second-order [[Partial Derivative|partial derivatives]]:

$$H_f(\mathbf{x}) = \left(\frac{\partial^2 f}{\partial x_i \partial x_j}\right)_{i,j} \in \mathbb{R}^{n \times n}$$

It is the Jacobian of the [[Gradient]] of $f$, and describes the local curvature of $f$.

**Properties**
- If the second partial derivatives are continuous, $H_f$ is symmetric.
- Second-order [[Taylor Expansion|Taylor]] approximation: $f(\mathbf{x} + \mathbf{h}) \approx f(\mathbf{x}) + \nabla f(\mathbf{x})^\top \mathbf{h} + \tfrac{1}{2}\mathbf{h}^\top H_f(\mathbf{x})\,\mathbf{h}$.
- At a [[Critical Point]] ($\nabla f = 0$):
  - $H_f$ [[Positive Definite Matrix|positive definite]]: local minimum.
  - $H_f$ negative definite: local maximum.
  - $H_f$ with eigenvalues of both signs: saddle point.