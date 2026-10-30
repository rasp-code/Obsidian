---
created: 2026-10-27
updated: 2026-10-28
---
**Self-supervised learning** is a learning setting where the targets are generated automatically from the data itself, without human annotation, and the model is trained as in [[Supervised Learning]] on these targets.

**Principle**
- A **pretext task** is built from unlabeled data: part of each example is hidden or transformed, and the model predicts it from the rest.
- The [[Signal]] is the error on this pretext task, measured by a [[Loss Function]].

**Properties**
- The dataset is unlabeled, as in [[Unsupervised Learning]], but the signal is supervised in form.
- The learned representations are reused for other tasks.
