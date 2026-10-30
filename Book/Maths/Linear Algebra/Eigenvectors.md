---
created: 2026-10-27
updated: 2026-10-28
---
An **eigenvector** of a square [[Matrix]] $A$ is a nonzero [[Vector]] $\mathbf{v}$ whose direction is unchanged by $A$: it is only scaled by a factor $\lambda$, its [[Eigenvalues|eigenvalue]].

$$A\mathbf{v} = \lambda\mathbf{v}$$

**Properties**
- Any nonzero multiple of an eigenvector is also an eigenvector for the same eigenvalue.
- The eigenvectors associated with a given eigenvalue, together with the zero vector, form a [[Vector Subspace]]: the **eigenspace**.
- Eigenvectors associated with distinct eigenvalues are [[Linear Independence|linearly independent]].
- A symmetric real matrix has an [[Orthogonality|orthonormal]] [[Basis]] of eigenvectors, so $A = Q\Lambda Q^\top$, with $Q$ the matrix of eigenvectors and $\Lambda$ the diagonal matrix of eigenvalues.