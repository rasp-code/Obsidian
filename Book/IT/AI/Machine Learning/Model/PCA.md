---
created: 2026-10-27
updated: 2026-10-28
---
**Principal component analysis (PCA)** is a linear [[Dimensionality Reduction]] method that projects the data onto the orthogonal directions of maximal [[Variance]].

**Method**
- Center the data: $X \leftarrow X - \bar{\mathbf{x}}$.
- Compute the covariance [[Matrix]] $C = \frac{1}{N} X^\top X$.
- The principal components are the [[Eigenvectors]] of $C$, sorted by decreasing [[Eigenvalues]] $\lambda_1 \geq \dots \geq \lambda_D$.
- Project onto the first $d$ components $V_d$: $Z = X V_d$.

**Properties**
- $\lambda_i$ is the variance along component $i$.
- Components are [[Orthogonality|orthogonal]]; the projected features are uncorrelated.
- It minimizes the reconstruction error of the [[Projection]].
- It is computed in practice with the [[SVD]] of $X$.
