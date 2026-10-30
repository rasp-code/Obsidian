---
created: 2026-10-26
updated: 2026-10-28
---
**Logistic regression** is a [[Model]] for binary [[Classification]] that estimates the [[Conditional Probability]] of the positive class with a linear function of the features followed by the [[Sigmoid|logistic function]]:

$$P(y = 1 \mid \mathbf{x}) = \sigma(\mathbf{w}^\top \mathbf{x} + b), \qquad \sigma(z) = \frac{1}{1 + e^{-z}}$$

See [[Weight]], [[Bias]], [[Exponential Function]].

**Condition**
- Binary label $y \in \{0, 1\}$.

**Properties**
- The log-odds are linear (see [[Logarithm]]): $\ln\dfrac{p}{1-p} = \mathbf{w}^\top \mathbf{x} + b$.
- Predicting class $1$ when $p \geq 0.5$ is equivalent to $\mathbf{w}^\top \mathbf{x} + b \geq 0$: the decision boundary is a hyperplane.

**Training**
- By [[MLE|maximum likelihood estimation]], i.e. by minimizing the binary [[Cross-Entropy]] [[Loss Function]]:
$$J = -\frac{1}{N}\sum_{i=1}^{N}\Big[y_i \ln p_i + (1 - y_i)\ln(1 - p_i)\Big]$$
- This loss is [[Convexity|convex]] but has no closed-form minimum: iterative optimization is used.

**Comparison**
- [[Linear Regression]] outputs the linear combination directly.
