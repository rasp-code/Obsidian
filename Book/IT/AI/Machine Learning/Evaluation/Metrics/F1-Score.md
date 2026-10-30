---
created: 2026-10-27
updated: 2026-10-28
---
The **F1-score** is the harmonic mean of [[Precision]] and [[Recall]].

$$F_1 = 2\,\frac{\mathrm{Precision} \cdot \mathrm{Recall}}{\mathrm{Precision} + \mathrm{Recall}} = \frac{2\,TP}{2\,TP + FP + FN}$$

**Properties**
- Values in $[0, 1]$; high only if both precision and recall are high.
- Ignores true negatives: suited to imbalanced classes.
