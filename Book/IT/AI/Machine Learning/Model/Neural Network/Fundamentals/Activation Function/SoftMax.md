---
created: 2026-10-27
updated: 2026-10-28
---
The **softmax** function turns a [[Vector]] of real scores (logits) into a [[Probability Distribution]] over $K$ components:

$$\mathrm{softmax}(\mathbf{z})_i = \frac{e^{z_i}}{\sum_{j=1}^{K} e^{z_j}}$$

**Properties**
- Outputs in $(0, 1)$, summing to $1$.
- It preserves the order of the scores.
- It is invariant to adding a constant: $\mathrm{softmax}(\mathbf{z} + c) = \mathrm{softmax}(\mathbf{z})$.
- For $K = 2$, it reduces to the [[Sigmoid]] of the difference of the scores.
