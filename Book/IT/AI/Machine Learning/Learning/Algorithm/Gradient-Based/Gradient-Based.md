---
created: 2026-10-28
updated: 2026-10-28
---
**Gradient-based algorithms** update the [[Parameters]] using the [[Gradient]] of the loss, moving them in the direction that decreases it.

**Algorithms**
- [[GD]]: step along the negative gradient over the whole dataset.
- [[SGD]]: gradient estimated on random examples.
- [[Momentum]]: accumulation of past gradients.
- [[RMSprop]]: per-parameter scaling of the step.
- [[Adam]]: combination of momentum and RMSprop.

**Related notions**
- [[Backpropagation]]: computation of the gradient in a neural network.
- [[Vanishing Gradient]], [[Exploding Gradient]]: instabilities of the gradient in deep networks.
