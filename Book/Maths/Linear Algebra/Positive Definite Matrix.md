---
created: 2026-10-28
updated: 2026-10-28
---
A symmetric [[Matrix]] $A \in \mathbb{R}^{n \times n}$ is **positive definite** if

$$\mathbf{x}^\top A \mathbf{x} > 0 \quad \text{for all } \mathbf{x} \neq 0$$

It is **positive semidefinite** if $\mathbf{x}^\top A \mathbf{x} \geq 0$ for all $\mathbf{x}$.

**Conditions**
- $A$ is symmetric: $A = A^\top$ (see [[Transpose]]).

**Equivalent characterizations** (symmetric $A$)
- All [[Eigenvalues]] are $> 0$ (positive definite), or $\geq 0$ (positive semidefinite).
- $A = B^\top B$ for some invertible matrix $B$ (positive definite), or for some matrix $B$ (positive semidefinite).

**Properties**
- A positive definite matrix is invertible, and its inverse is positive definite (see [[Inverse Matrix]]).
- Its diagonal entries are $> 0$.
- The sum of two positive definite matrices is positive definite.
- It defines an [[Inner Product]]: $\langle \mathbf{x}, \mathbf{y} \rangle = \mathbf{x}^\top A \mathbf{y}$.

**Related**
- Negative definite: $-A$ is positive definite.
- Indefinite: $\mathbf{x}^\top A \mathbf{x}$ takes both signs.