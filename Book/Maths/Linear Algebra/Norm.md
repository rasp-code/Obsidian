---
created: 2026-10-28
updated: 2026-10-28
---
A **norm** on a [[Vector Space]] $V$ is a function $\|\cdot\| : V \to \mathbb{R}$ that measures the length of a vector.

**Conditions** (for all $x, y \in V$ and $a \in \mathbb{K}$)
- Positive definiteness: $\|x\| \geq 0$, and $\|x\| = 0$ if and only if $x = 0$.
- Homogeneity: $\|ax\| = |a|\,\|x\|$.
- Triangle inequality: $\|x + y\| \leq \|x\| + \|y\|$.

**Common norms on $\mathbb{R}^n$**
- $\ell_1$: $\|\mathbf{x}\|_1 = \sum_i |x_i|$.
- $\ell_2$ (Euclidean): $\|\mathbf{x}\|_2 = \sqrt{\sum_i x_i^2}$.
- $\ell_\infty$: $\|\mathbf{x}\|_\infty = \max_i |x_i|$.
- $\ell_p$ ($p \geq 1$): $\|\mathbf{x}\|_p = \left(\sum_i |x_i|^p\right)^{1/p}$.

**Properties**
- A **unit vector** has norm $1$. Any nonzero $x$ gives the unit vector $x / \|x\|$.
- It induces a distance: $d(x, y) = \|x - y\|$.
- Reverse triangle inequality: $\big|\,\|x\| - \|y\|\,\big| \leq \|x - y\|$.