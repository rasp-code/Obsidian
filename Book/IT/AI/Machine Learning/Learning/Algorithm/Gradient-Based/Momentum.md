---
created: 2026-10-28
updated: 2026-10-28
---
**Momentum** is a modification of gradient descent that accumulates a velocity, an exponential moving average of past gradients, to accelerate and smooth the updates:

$$\mathbf{v}_{t+1} = \beta\, \mathbf{v}_t + \nabla_\theta J(\theta_t), \qquad \theta_{t+1} = \theta_t - \eta\, \mathbf{v}_{t+1}$$

where $\beta \in [0, 1)$ is the momentum coefficient.

**Properties**
- Accelerates in directions where the gradient is consistent.
- Dampens oscillations in directions where it changes sign.
