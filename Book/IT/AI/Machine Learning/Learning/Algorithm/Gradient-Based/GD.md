---
created: 2026-10-27
updated: 2026-10-28
---
**Gradient descent (GD)** is an iterative [[Optimization]] algorithm that minimizes a function by moving the parameters in the direction opposite to its [[Gradient]]:

$$\theta_{t+1} = \theta_t - \eta\, \nabla_\theta J(\theta_t)$$

where $\eta$ is the [[Learning Rate]] and $J$ the loss over the whole [[Dataset]].

**Properties**
- The negative gradient is the direction of steepest local decrease.
- For a [[Convexity|convex]] function and a suitable $\eta$, it converges to the [[Global Minimum]]; otherwise to a [[Local Minimum]] or a [[Saddle Point]].
- Each step uses the whole dataset: costly for large $N$.
