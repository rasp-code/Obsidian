---
created: 2026-10-27
updated: 2026-10-28
---
**Adam** (Adaptive Moment Estimation) is a gradient-based [[Update Rule]] that combines [[Momentum]] and [[RMSprop]]: each parameter gets an adaptive step size.

With $g_t = \nabla_\theta J(\theta_t)$, operations element-wise:
$$m_t = \beta_1 m_{t-1} + (1 - \beta_1)\, g_t, \qquad v_t = \beta_2 v_{t-1} + (1 - \beta_2)\, g_t^2$$
$$\hat{m}_t = \frac{m_t}{1 - \beta_1^t}, \qquad \hat{v}_t = \frac{v_t}{1 - \beta_2^t}, \qquad \theta_{t+1} = \theta_t - \eta\, \frac{\hat{m}_t}{\sqrt{\hat{v}_t} + \epsilon}$$

**Elements**
- $m_t$: moving average of gradients (first moment: direction).
- $v_t$: moving average of squared gradients (second moment: scale).
- $\hat{m}_t, \hat{v}_t$: correction of the bias due to zero initialization.
- Default values: $\beta_1 = 0.9$, $\beta_2 = 0.999$, $\epsilon = 10^{-8}$.
