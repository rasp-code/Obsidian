---
created: 2026-10-22
updated: 2026-10-28
---
A **loss function** $L(\hat{y}, y)$ measures the discrepancy between a model [[Output]] $\hat{y}$ and the target $y$ (the [[Label]]) for one example.

**Empirical risk (cost function)**
- The average loss over a [[Dataset]] of $N$ examples, as a function of the parameters $\theta$:
$$J(\theta) = \frac{1}{N} \sum_{i=1}^{N} L\big(f_\theta(x_i),\, y_i\big)$$
- Training is the [[Optimization]] problem $\min_\theta J(\theta)$.

**Properties**
- Usually $L \geq 0$, with $L = 0$ when the output matches the target.
- For gradient-based learning, $L$ must be differentiable with respect to the parameters (see [[Gradient]]).
- Without labels, the loss is defined from the input itself or from a reward.

**Comparison**
- A [[Metrics|metric]] measures performance for [[Evaluation]] and need not be differentiable.
