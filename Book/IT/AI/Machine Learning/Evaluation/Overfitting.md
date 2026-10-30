---
created: 2026-10-27
updated: 2026-10-28
---
**Overfitting** occurs when a model fits the training data too closely, including its noise, and generalizes poorly.

**Symptom**
- Low training error, high validation error: large [[Generalization]] gap.

**Cause**
- A model too complex for the amount of data: high variance (see [[Bias-Variance Tradeoff]]).

**Remedies**
- More data, [[Data Augmentation]], [[Regularization]], simpler model.
