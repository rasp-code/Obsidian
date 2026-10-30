---
created: 2026-10-28
updated: 2026-10-28
---
The **singular value decomposition** (SVD) of a [[Matrix]] $A \in \mathbb{R}^{m \times n}$ is its factorization

$$A = U \Sigma V^\top$$

**Factors**
- $U \in \mathbb{R}^{m \times m}$ is orthogonal ($U^\top U = I$); its columns are the **left singular vectors**.
- $V \in \mathbb{R}^{n \times n}$ is orthogonal ($V^\top V = I$); its columns are the **right singular vectors**.
- $\Sigma \in \mathbb{R}^{m \times n}$ is zero except on its diagonal, which contains the **singular values** $\sigma_1 \geq \sigma_2 \geq \dots \geq 0$.

The columns of $U$ and of $V$ are orthonormal families (see [[Orthogonality]], [[Transpose]]).

**Properties**
- It exists for every matrix, unlike the [[Eigendecomposition]].
- The singular values are unique.
- $\sigma_i = \sqrt{\lambda_i}$, where $\lambda_i$ are the [[Eigenvalues]] of $A^\top A$.
- $\mathrm{rank}(A)$ is the number of nonzero singular values (see [[Rank]]).
- Sum form: $A = \sum_i \sigma_i\,\mathbf{u}_i \mathbf{v}_i^\top$.