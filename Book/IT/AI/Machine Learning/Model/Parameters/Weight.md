---
created: 2026-10-25
updated: 2026-10-28
---
A **weight** is a [[Parameters|parameter]] that multiplies an input value, and so scales its contribution to a weighted sum, a [[Linear Combination]] of the inputs:

$$z = \sum_{i=1}^{d} w_i\,x_i = \mathbf{w}^\top \mathbf{x}$$

**Properties**
- The magnitude of $w_i$ gives the influence of $x_i$ on the result; its sign, the direction of this influence.
- The weights of a layer form a [[Matrix]] $W$.

**Comparison**
- The [[Bias]] is added to the weighted sum instead of multiplying an input.
