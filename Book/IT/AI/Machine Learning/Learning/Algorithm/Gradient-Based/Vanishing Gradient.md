---
created: 2026-10-28
updated: 2026-10-28
---
The **vanishing gradient** problem occurs when gradients shrink exponentially as they are propagated backward, so that the first layers barely learn.

**Cause**
- [[Backpropagation]] multiplies one factor per layer; if these factors are smaller than $1$, their product tends to $0$.
- Saturating activations, such as the [[Sigmoid]] ($\sigma' \leq 0.25$), produce such factors.

**Remedies**
- Non-saturating activations ([[ReLU]]), suitable initialization, [[Batch Normalization]], residual connections, gated cells ([[LSTM]], [[GRU]]).
