---
created: 2026-10-27
updated: 2026-10-28
---
**Mean pooling** (average pooling) is a [[Pooling Layer]] that keeps the average value of each window $\mathcal{W}_{i,j}$:

$$y_{i,j} = \frac{1}{|\mathcal{W}_{i,j}|} \sum_{(m, n) \in \mathcal{W}_{i,j}} x_{m,n}$$

**Properties**
- It keeps information from all elements.
- The gradient is distributed equally over the window.

**Comparison**
- [[Max Pooling]] keeps only the strongest activation.
