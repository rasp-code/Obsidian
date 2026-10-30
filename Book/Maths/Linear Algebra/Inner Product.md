---
created: 2026-10-28
updated: 2026-10-28
---
An **inner product** on a real [[Vector Space]] $V$ is a function $\langle \cdot, \cdot \rangle : V \times V \to \mathbb{R}$ that generalizes the notions of length and angle.

**Conditions** (for all $x, y, z \in V$ and $a \in \mathbb{R}$)
- Symmetry: $\langle x, y \rangle = \langle y, x \rangle$.
- Linearity in the first argument: $\langle ax + y, z \rangle = a\langle x, z \rangle + \langle y, z \rangle$ (hence in the second as well, by symmetry).
- Positive definiteness: $\langle x, x \rangle > 0$ for $x \neq 0$.

**Induced norm**
- $\|x\| = \sqrt{\langle x, x \rangle}$ is a [[Norm]].

**Properties**
- Cauchy–Schwarz inequality: $|\langle x, y \rangle| \leq \|x\|\,\|y\|$.
- Angle between nonzero vectors: $\cos\theta = \dfrac{\langle x, y \rangle}{\|x\|\,\|y\|}$.

**Examples**
- Standard inner product on $\mathbb{R}^n$: $\langle \mathbf{x}, \mathbf{y} \rangle = \sum_i x_i y_i$.
- Weighted inner product on $\mathbb{R}^n$: $\langle \mathbf{x}, \mathbf{y} \rangle = \mathbf{x}^\top A \mathbf{y}$, with $A$ symmetric positive definite.