---
created: 2026-10-28
updated: 2026-10-28
---
The **determinant** of a square [[Matrix]] $A \in \mathbb{R}^{n \times n}$ is a scalar $\det(A)$ that is the unique function of the columns of $A$ satisfying:
- Linear in each column.
- Alternating: it is $0$ if two columns are equal.
- Normalized: $\det(I) = 1$.

**Small cases**
- $2 \times 2$: $\det\begin{pmatrix} a & b \\ c & d \end{pmatrix} = ad - bc$.
- Triangular or diagonal matrix: product of the diagonal entries.

**Geometric meaning**
- For the [[Linear Map]] $\mathbf{x} \mapsto A\mathbf{x}$, $|\det(A)|$ is the factor by which volumes are scaled.
- The sign indicates whether orientation is preserved ($+$) or reversed ($-$).

**Properties**
- $\det(AB) = \det(A)\det(B)$.
- $\det(A^\top) = \det(A)$ (see [[Transpose]]).
- $\det(cA) = c^n \det(A)$.
- Swapping two rows or two columns changes the sign.
- $\det(A) = 0$ if and only if the columns of $A$ are linearly dependent (see [[Linear Independence]]).