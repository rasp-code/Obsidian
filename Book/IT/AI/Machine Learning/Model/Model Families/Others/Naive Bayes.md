---
created: 2026-10-27
updated: 2026-10-28
---
**Naive Bayes** is a probabilistic classifier that applies [[Bayes' Theorem]] with the "naive" assumption that the features are [[Independence|conditionally independent]] given the class:

$$P(y \mid \mathbf{x}) \propto P(y) \prod_{j=1}^{d} P(x_j \mid y), \qquad \hat{y} = \arg\max_y \; P(y) \prod_{j=1}^{d} P(x_j \mid y)$$

**Properties**
- Training reduces to estimating $P(y)$ and each $P(x_j \mid y)$ from frequencies.
- The independence assumption is rarely true, yet the predicted class is often correct.
