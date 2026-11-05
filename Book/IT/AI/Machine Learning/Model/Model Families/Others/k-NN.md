---
created: 2026-10-27
updated: 2026-10-28
---
**k-nearest neighbors (k-NN)** is a non-parametric [[Model]] that predicts from the $k$ training examples closest to the input, for a [[Distance]].

**Prediction**
- [[Classification]]: majority class among the $k$ neighbors $\mathcal{N}_k(x)$.
- [[Regression]]: mean of their values:
$$\hat{y} = \frac{1}{k}\sum_{i \in \mathcal{N}_k(x)} y_i$$

**Properties**
- No training: the dataset is stored, and the cost is paid at prediction.
- Small $k$ leads to [[Overfitting]], large $k$ to [[Underfitting]].
