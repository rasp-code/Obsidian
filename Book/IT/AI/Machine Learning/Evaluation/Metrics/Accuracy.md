---
created: 2026-10-27
updated: 2026-10-28
---
**Accuracy** is the proportion of correct predictions of a classifier.

$$\mathrm{Accuracy} = \frac{TP + TN}{TP + TN + FP + FN}$$

See [[Confusion Matrix]].

**Properties**
- Values in $[0, 1]$.
- Misleading with imbalanced classes: always predicting the majority class gives a high accuracy.
