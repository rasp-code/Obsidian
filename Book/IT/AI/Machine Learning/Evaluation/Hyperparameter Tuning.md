---
created: 2026-10-28
updated: 2026-10-28
---
**Hyperparameter tuning** is the search for the [[Hyperparameter]] values $\lambda$ that give the best validation performance:

$$\lambda^* = \arg\min_{\lambda} \; \mathrm{Err}_{\text{val}}\big(\theta^*(\lambda)\big)$$

where $\theta^*(\lambda)$ are the [[Parameters]] learned with $\lambda$.

**Principle**
- Candidate values are tried, each with a full training, and compared on a validation set or by [[Cross-Validation]], never on the test set.
