---
created: 2026-10-27
updated: 2026-10-28
---
An **eigenvalue** of a square [[Matrix]] $A \in \mathbb{R}^{n \times n}$ is a [[Scalar|scalar]] $\lambda$ for which there exists a nonzero [[Vector]] $\mathbf{v}$ (an [[Eigenvectors|eigenvector]]) such that

$$A\mathbf{v} = \lambda\mathbf{v}$$

**Computation**: eigenvalues are the roots of the characteristic polynomial
$$\det(A - \lambda I) = 0$$
where $\det$ is the [[Determinant]]. A matrix of size $n \times n$ has at most $n$ distinct eigenvalues.

**Properties**
- $\sum_i \lambda_i = \mathrm{tr}(A)$ and $\prod_i \lambda_i = \det(A)$ (counted with multiplicity).
- $A$ is invertible if and only if no eigenvalue is zero.
- A symmetric real matrix has only real eigenvalues.