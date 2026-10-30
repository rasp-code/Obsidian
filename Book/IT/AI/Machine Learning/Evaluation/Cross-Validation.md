---
created: 2026-10-27
updated: 2026-10-28
---
**Cross-validation** estimates the [[Generalization]] performance of a model by training and evaluating it on several splits of the [[Dataset]].

**k-fold cross-validation**
- Split the data into $k$ folds of equal size.
- For each fold $i$: train on the $k - 1$ other folds, evaluate on fold $i$, giving a score $s_i$.
- Final score:
$$\mathrm{CV} = \frac{1}{k}\sum_{i=1}^{k} s_i$$

**Properties**
- Every example is used for both training and validation, at the cost of $k$ trainings.
- Used for [[Hyperparameter Tuning]] and model selection; the test set stays separate.
