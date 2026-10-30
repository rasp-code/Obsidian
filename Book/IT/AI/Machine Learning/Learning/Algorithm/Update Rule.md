---
created: 2026-10-27
updated: 2026-10-28
---
An **update rule** computes the new values of the [[Parameters]] of a model from their current values and from information about the [[Loss Function]]:

$$\theta_{t+1} = \theta_t + \Delta_t$$

where $\theta_t$ are the parameters at step $t$ and $\Delta_t$ the update computed by the rule.

**Elements**
- Current parameters $\theta_t$.
- Information on the loss: its value, its gradient, or a reward.
- [[Hyperparameter|Hyperparameters]] of the rule, such as the [[Learning Rate]].
- Possibly an internal state carried across steps.

**Properties**
- Applied iteratively from initial values $\theta_0$ until a stopping criterion is met.
- The sequence of updates solves an [[Optimization]] problem: decreasing the loss.
