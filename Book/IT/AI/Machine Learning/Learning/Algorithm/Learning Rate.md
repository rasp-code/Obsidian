---
created: 2026-10-27
updated: 2026-10-28
---
The **learning rate** $\eta > 0$ is the [[Hyperparameter]] that sets the size of each step of a gradient-based [[Update Rule]]:

$$\theta_{t+1} = \theta_t - \eta\, \nabla_\theta J(\theta_t)$$

**Properties**
- Too large: oscillations or divergence.
- Too small: very slow convergence.
- It may vary during training according to a schedule.
