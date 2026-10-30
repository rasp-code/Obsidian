---
created: 2026-10-27
updated: 2026-10-28
---
**Batch normalization** is a layer that normalizes each feature over a [[Mini-Batch]], then rescales it with learned parameters:

$$\hat{x}_i = \frac{x_i - \mu_B}{\sqrt{\sigma_B^2 + \epsilon}}, \qquad y_i = \gamma\, \hat{x}_i + \beta$$

**Elements**
- $\mu_B, \sigma_B^2$: mean and variance over the batch.
- $\gamma, \beta$: learned scale and shift.
- At inference, running averages of $\mu$ and $\sigma^2$ computed during training are used.

**Properties**
- It stabilizes and speeds up training.
