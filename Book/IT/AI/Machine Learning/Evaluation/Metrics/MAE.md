---
created: 2026-10-27
updated: 2026-10-28
---
The **mean absolute error (MAE)** is the average absolute difference between predictions and targets in [[Regression]].

$$\mathrm{MAE} = \frac{1}{N}\sum_{i=1}^{N} |y_i - \hat{y}_i|$$

**Properties**
- Same unit as the target.
- Robust to outliers: errors count linearly.
- The best constant prediction is the median.

**Comparison**
- [[MSE]] penalizes large errors more.
