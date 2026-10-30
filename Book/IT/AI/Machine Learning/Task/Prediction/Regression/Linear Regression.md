---
created: 2026-10-26
updated: 2026-10-28
---
**Linear regression** is a [[Model]] for [[Regression]] where the output is a linear function of the features plus a bias:

$$\hat{y} = \mathbf{w}^\top \mathbf{x} + b$$

See [[Weight]], [[Bias]], [[Dot Product]].

**Matrix form**
- For a data [[Matrix]] $X \in \mathbb{R}^{N \times d}$, bias absorbed as a constant column: $\hat{\mathbf{y}} = X\mathbf{w}$.

**Training (least squares)**
- Minimizes the mean squared error [[Loss Function]]:
$$J(\mathbf{w}) = \frac{1}{N}\,\|X\mathbf{w} - \mathbf{y}\|_2^2$$
- Closed-form solution (normal equations), see [[Transpose]], [[Inverse Matrix]]:
$$\mathbf{w} = (X^\top X)^{-1} X^\top \mathbf{y}$$

**Condition for the closed form**
- $X^\top X$ is invertible, i.e. $X$ has full column [[Rank]].

**Properties**
- Linear in the parameters, not necessarily in the inputs: features can be nonlinear transformations of the raw inputs.
- $X\mathbf{w}$ is the orthogonal [[Projection]] of $\mathbf{y}$ onto the column space of $X$.
