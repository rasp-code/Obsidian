---
created: 2026-10-27
updated: 2026-10-28
---
**L1 regularization** (Lasso) adds to the loss a penalty proportional to the sum of the absolute values of the weights:

$$J_{\text{reg}}(\mathbf{w}) = J(\mathbf{w}) + \lambda\, \|\mathbf{w}\|_1, \qquad \|\mathbf{w}\|_1 = \sum_i |w_i|$$

See [[Norm]].

**Properties**
- Produces **sparse** solutions: many weights exactly $0$, hence feature selection.
- Not differentiable at $0$.
- Equivalent to a Laplace prior on the weights (see [[MAP]]).

**Comparison**
- [[L2 (Ridge)]] shrinks the weights without setting them to $0$.
