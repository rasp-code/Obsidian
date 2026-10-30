---
created: 2026-10-25
updated: 2026-10-28
---
A **bias** is a [[Parameters|parameter]] added to a weighted sum, independently of the input:

$$z = \mathbf{w}^\top \mathbf{x} + b$$

where $b$ is the bias and $\mathbf{w}$ the [[Weight|weights]].

**Properties**
- It shifts the result by a constant: without it, the function is forced through the origin.
- It can be absorbed into the weights by adding a constant [[Feature]] equal to $1$.

**Scope**
- Here, "bias" is this additive parameter, not the statistical bias of an estimator.
