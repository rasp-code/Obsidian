---
created: 2026-10-25
updated: 2026-10-28
---
**Learning** is the process that adjusts the [[Parameters]] $\theta$ of a [[Model]] from [[Data]], by minimizing an objective:

$$\theta^* = \arg\min_\theta \; J(\theta) + \lambda\, \Omega(\theta)$$

**Components**
- [[Signal]]: where the learning information comes from.
- [[Objective]]: what is minimized.
- [[Algorithm]]: how the parameters are updated.
- [[Regime]]: how training is organized in phases.
