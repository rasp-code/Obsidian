---
created: 2026-10-27
updated: 2026-10-28
---
**L2 regularization** (Ridge, weight decay) adds to the loss a penalty proportional to the squared Euclidean [[Norm]] of the weights:

$$J_{\text{reg}}(\mathbf{w}) = J(\mathbf{w}) + \lambda\, \|\mathbf{w}\|_2^2, \qquad \|\mathbf{w}\|_2^2 = \sum_i w_i^2$$

**Properties**
- Shrinks all weights toward $0$, without making them exactly $0$.
- A gradient step becomes $\mathbf{w} \leftarrow (1 - 2\eta\lambda)\,\mathbf{w} - \eta\, \nabla J$: the weights decay.
- Equivalent to a [[Gaussian Distribution|Gaussian]] prior on the weights (see [[MAP]]).

**Comparison**
- [[L1 (Lasso)]] produces sparse weights.
