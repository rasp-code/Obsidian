---
created: 2026-10-27
updated: 2026-10-28
---
**Generalization** is the ability of a model to perform well on new data, drawn from the same [[Probability Distribution]] as the training data but not seen during training.

**Generalization gap**
$$R(\theta) - \hat{R}(\theta), \qquad R(\theta) = \mathbb{E}_{(x, y) \sim p}\big[L(f_\theta(x), y)\big]$$
- $R$: true risk; $\hat{R}$: empirical risk on the training set (see [[Expectation]], [[Loss Function]]).
- Estimated on a test set; a large gap indicates [[Overfitting]].

**Assumption**
- Training and test data follow the same distribution.
