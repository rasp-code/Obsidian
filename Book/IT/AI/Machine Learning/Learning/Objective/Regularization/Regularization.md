---
created: 2026-10-26
updated: 2026-10-28
---
**Regularization** is any technique that reduces [[Overfitting]] by constraining the model, often by adding a penalty to the loss:

$$J_{\text{reg}}(\theta) = J(\theta) + \lambda\, \Omega(\theta)$$

where $\Omega$ penalizes complexity and $\lambda \geq 0$ is its strength (a [[Hyperparameter]]).

**Techniques**
- [[L1 (Lasso)]]: penalty on absolute weights.
- [[L2 (Ridge)]]: penalty on squared weights.
- [[Dropout]]: random deactivation of neurons.
- [[Early Stopping]]: training stopped at the best validation score.

**Properties**
- It trades a little more bias for lower variance (see [[Bias-Variance Tradeoff]]).
