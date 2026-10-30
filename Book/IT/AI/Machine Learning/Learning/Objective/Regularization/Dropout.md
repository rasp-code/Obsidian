---
created: 2026-10-27
updated: 2026-10-28
---
**Dropout** is a [[Regularization]] technique for [[Neural Network|neural networks]] that randomly deactivates neurons during training.

**Principle**
- At each training step, each neuron is set to $0$ with probability $p$ (the drop rate), and the kept outputs are scaled so that the expected activation is unchanged:
$$\tilde{\mathbf{h}} = \frac{\mathbf{m} \odot \mathbf{h}}{1 - p}, \qquad m_i \sim \mathrm{Bernoulli}(1 - p)$$
- At inference, all neurons are used.

**Properties**
- It prevents neurons from relying on specific other neurons (co-adaptation).
