---
created: 2026-10-27
updated: 2026-10-28
---
**Fine-tuning** is the continuation of the training of a pre-trained model on a smaller, task-specific [[Dataset]], to adapt it to a new [[Task]].

**Principle**
- Training starts from the [[Parameters]] obtained by [[Pre-Training]].
- It uses the target data, usually with a small [[Learning Rate]].
- All parameters, or only some of them, are updated.

**Properties**
- It can degrade the pre-trained knowledge (catastrophic forgetting).
