---
created: 2026-10-22
updated: 2026-10-28
---
A **random forest** is an ensemble of [[Decision Tree|decision trees]] trained independently on random variations of the data, whose predictions are averaged (regression) or voted (classification).

**Sources of randomness**
- Bagging: each tree is trained on a bootstrap sample, drawn with replacement.
- Feature subsampling: each split considers a random subset of features.

**Properties**
- Averaging decorrelated trees reduces variance without increasing bias.
- Examples left out of a tree's sample (out-of-bag) give a validation estimate.

**Comparison**
- [[Gradient Boosting]] builds trees sequentially to reduce bias.
