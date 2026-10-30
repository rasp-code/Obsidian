---
created: 2026-10-27
updated: 2026-10-28
---
The **mean squared error (MSE)** is the average squared difference between predictions and targets in [[Regression]].

$$\mathrm{MSE} = \frac{1}{N}\sum_{i=1}^{N} (y_i - \hat{y}_i)^2$$

**Properties**
- Penalizes large errors strongly: sensitive to outliers.
- Differentiable and [[Convexity|convex]] in the prediction.
- The best constant prediction is the mean (see [[Expectation]]).
- $\mathrm{RMSE} = \sqrt{\mathrm{MSE}}$ has the unit of the target.

**Comparison**
- [[MAE]] is more robust to outliers.
