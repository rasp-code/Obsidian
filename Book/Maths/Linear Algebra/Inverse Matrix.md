---
created: 2026-10-28
updated: 2026-10-28
---
The **inverse** of a square [[Matrix]] $A \in \mathbb{R}^{n \times n}$ is the matrix $A^{-1}$ such that

$$A A^{-1} = A^{-1} A = I$$

where $I$ is the identity matrix. A matrix that has an inverse is **invertible** (or non-singular).

**Equivalent conditions for invertibility**
- $\det(A) \neq 0$ (see [[Determinant]]).
- $\mathrm{rank}(A) = n$ (see [[Rank]]).
- The columns of $A$ are linearly independent (see [[Linear Independence]]).
- The [[Linear Map]] $\mathbf{x} \mapsto A\mathbf{x}$ is bijective.

**Properties**
- The inverse is unique.
- $(A^{-1})^{-1} = A$.
- $(AB)^{-1} = B^{-1}A^{-1}$.
- $(A^\top)^{-1} = (A^{-1})^\top$ (see [[Transpose]]).
- If $A$ is invertible, $A\mathbf{x} = \mathbf{b}$ has the unique solution $\mathbf{x} = A^{-1}\mathbf{b}$.