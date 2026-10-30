---
created: 2026-10-25
updated: 2026-10-28
---
**Forecasting** is the [[Prediction]] task of estimating future values of a time series from its past observations.

**Formulation**
- Given observations $y_1, \dots, y_t$, predict $y_{t+h}$, where $h$ is the **horizon**.

**Conditions**
- Observations are ordered in time.
- Successive observations are dependent: the i.i.d. assumption does not hold (see [[Independence]]).

**Comparison**
- [[Regression]] also predicts numerical values, but without temporal ordering of the examples.
