---
created: 2026-10-25
updated: 2026-10-28
---
**Supervised learning** is a learning setting where the [[Signal]] comes from [[Label|labels]]: the model learns a function from [[Input|inputs]] to [[Output|outputs]] using a [[Dataset]] of input-label pairs $\{(x_i, y_i)\}_{i=1}^{N}$.

**Principle**
- The error between the model output $f_\theta(x_i)$ and the label $y_i$ is measured by a [[Loss Function]].
- The [[Parameters]] $\theta$ minimize the average loss:
$$\min_\theta \frac{1}{N} \sum_{i=1}^{N} L\big(f_\theta(x_i), y_i\big)$$

**Properties**
- The signal is instructive: it gives the expected answer.
