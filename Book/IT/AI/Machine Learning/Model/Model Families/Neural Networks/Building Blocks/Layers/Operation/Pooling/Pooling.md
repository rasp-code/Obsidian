---
created: 2026-10-27
updated: 2026-10-28
---
A **pooling layer** reduces the spatial size of feature maps by summarizing each window with a single value.

**Pooling functions**
- [[Max Pooling]]: maximum of the window.
- [[Mean Pooling]]: average of the window.

**Properties**
- It has no learned [[Parameters]].
- It is applied per channel: the number of channels is unchanged.
- It gives invariance to small translations.
