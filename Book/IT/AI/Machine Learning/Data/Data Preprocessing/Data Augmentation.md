---
created: 2026-10-25
updated: 2026-10-28
---
**Data augmentation** creates new training examples by applying label-preserving transformations to existing ones.

**Principle**
- The transformations encode invariances the model should learn.
- It acts as [[Regularization]]: it reduces [[Overfitting]].

**Conditions**
- The transformation must not change the [[Label]].
- It is applied to the training set only.
