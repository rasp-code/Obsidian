---
created: 2026-10-27
updated: 2026-10-28
---
**Early stopping** is a [[Regularization]] technique that stops training when the performance on a validation set stops improving.

**Principle**
- The validation loss is evaluated after each [[Epoch]].
- Training stops if it has not improved for $k$ consecutive epochs (the **patience**).
- The parameters of the best epoch are kept.

**Properties**
- It prevents [[Overfitting]], where the validation loss rises while the training loss keeps decreasing.
