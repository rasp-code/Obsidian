---
created: 2026-10-27
updated: 2026-10-28
---
**Max pooling** is a [[Pooling Layer]] that keeps the maximum value of each window $\mathcal{W}_{i,j}$:

$$y_{i,j} = \max_{(m, n) \in \mathcal{W}_{i,j}} x_{m,n}$$

**Properties**
- It detects whether a feature is present, wherever it is in the window.
- The gradient flows only to the maximal element.

**Comparison**
- [[Mean Pooling]] keeps information from all elements.
