---
created: 2026-10-26
updated: 2026-10-28
---
**Data preprocessing** is the set of operations that turn raw [[Data]] into a [[Dataset]] usable by a [[Model]].

**Steps**
- [[Data Cleaning]]: fix errors, missing values, duplicates.
- [[Data Transformation]]: scale and encode values.
- [[Feature Engineering]]: create and select features.
- [[Data Reduction]]: reduce size or dimension.
- [[Data Sampling]]: select or rebalance examples.
- [[Data Splitting]]: separate training, validation and test sets.
- [[Data Augmentation]]: generate new training examples.

**Condition**
- Statistics used by preprocessing (means, scales) are computed on the training set only, then applied to the other sets, to avoid **data leakage**.
