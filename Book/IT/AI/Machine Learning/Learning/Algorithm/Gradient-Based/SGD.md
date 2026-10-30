---
created: 2026-10-27
updated: 2026-10-28
---
**Stochastic gradient descent (SGD)** is a variant of [[GD]] where the gradient is estimated on one random example, or a [[Mini-Batch]], instead of the whole dataset:

$$\theta_{t+1} = \theta_t - \eta\, \nabla_\theta L\big(f_\theta(x_i), y_i\big), \qquad i \text{ drawn at random}$$

**Properties**
- Unbiased but noisy estimate of the full [[Gradient]] (see [[Expectation]]).
- Much cheaper per update: scales to large datasets.
- Converges only with a decreasing [[Learning Rate]]; otherwise it oscillates near the minimum.
