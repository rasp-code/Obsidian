---
created: 2026-10-25
updated: 2026-10-28
---
**Data splitting** divides a [[Dataset]] into disjoint subsets with distinct roles.

**Subsets**
- Training set: fits the [[Parameters]].
- Validation set: selects the [[Hyperparameter|hyperparameters]] and the model.
- Test set: estimates the final [[Generalization]] performance; used once.

**Conditions**
- No information from the validation or test sets may leak into training.
- Time series are split chronologically.
