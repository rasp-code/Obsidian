---
created: 2026-10-25
updated: 2026-10-28
---
**Clustering** is the [[Structure]] task of partitioning the examples of a [[Dataset]] into groups (**clusters**) such that examples in the same cluster are more similar to each other than to those of other clusters.

**Formulation**
- Hard clustering: an assignment $c : \mathcal{D} \to \{1, \dots, k\}$; the clusters are disjoint and cover $\mathcal{D}$.
- Soft clustering: each example has a degree of membership in each cluster.

**Conditions**
- A notion of similarity or [[Distance]] between examples.
- No [[Label|labels]].

**Properties**
- There is no single correct clustering: the result depends on the chosen similarity and method.
