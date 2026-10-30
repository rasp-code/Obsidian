---
created: 2026-10-28
updated: 2026-10-28
---
**RMSprop** is a gradient-based [[Update Rule]] that divides the step of each parameter by a moving average of its squared gradients, giving an adaptive [[Learning Rate]] per parameter.

With $g_t = \nabla_\theta J(\theta_t)$, operations element-wise:
$$s_t = \beta\, s_{t-1} + (1 - \beta)\, g_t^2, \qquad \theta_{t+1} = \theta_t - \frac{\eta}{\sqrt{s_t} + \epsilon}\, g_t$$

**Properties**
- Parameters with large gradients get smaller steps, and conversely.
