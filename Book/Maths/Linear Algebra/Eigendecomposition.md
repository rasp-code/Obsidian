---
created: 2026-10-28
updated: 2026-10-28
---
The **eigendecomposition** (or diagonalization) of a square [[Matrix]] $A \in \mathbb{R}^{n \times n}$ is its factorization

$$A = P D P^{-1}$$

where $D$ is the diagonal matrix of the [[Eigenvalues]] of $A$, and the columns of $P$ are the corresponding [[Eigenvectors]].

**Condition**
- $A$ has $n$ linearly independent eigenvectors (see [[Linear Independence]]), i.e. they form a [[Basis]] of $\mathbb{R}^n$. $A$ is then **diagonalizable**, and $P$ is invertible (see [[Inverse Matrix]]).

**Properties**
- Not every square matrix is diagonalizable, e.g. $\begin{pmatrix} 1 & 1 \\ 0 & 1 \end{pmatrix}$.
- $n$ distinct eigenvalues are sufficient.
- Powers: $A^k = P D^k P^{-1}$.

**Symmetric real matrices**
- Always diagonalizable, with $A = Q \Lambda Q^\top$, where $Q$ has orthonormal columns (see [[Orthogonality]], [[Transpose]]) and $\Lambda$ is diagonal.