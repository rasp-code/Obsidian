---
created: 2026-10-28
updated: 2026-10-28
---
The **exploding gradient** problem occurs when gradients grow exponentially as they are propagated backward, making training unstable.

**Cause**
- [[Backpropagation]] multiplies one factor per layer; if these factors are larger than $1$, their product explodes.

**Remedy**
- Gradient clipping: if $\|g\| > c$, then (see [[Norm]])
$$g \leftarrow c\,\frac{g}{\|g\|}$$
