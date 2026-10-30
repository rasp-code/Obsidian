---
created: 2026-10-27
updated: 2026-10-28
---
**k-means** is a [[Clustering]] algorithm that partitions the data into $k$ clusters $C_j$, each represented by its centroid (mean) $\boldsymbol{\mu}_j$.

**Objective**
$$\min_{C_1, \dots, C_k} \sum_{j=1}^{k} \sum_{x \in C_j} \|x - \boldsymbol{\mu}_j\|^2$$

**Algorithm**
- Initialize $k$ centroids.
- Assign each point to its nearest centroid.
- Recompute each centroid as the mean of its points.
- Repeat until the assignments no longer change.

**Properties**
- It always converges, but to a [[Local Minimum]] that depends on the initialization.
- $k$ must be chosen beforehand.
