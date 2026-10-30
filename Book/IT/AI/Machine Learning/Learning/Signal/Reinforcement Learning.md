---
created: 2026-10-25
updated: 2026-10-28
---
**Reinforcement learning** is a learning setting where an [[Intelligent Agent|agent]] learns to act by interacting with an environment and receiving a numerical **reward**, which constitutes the [[Signal]].

**Elements**
- Agent: the decision maker.
- Environment: what the agent interacts with.
- State: the description of the situation.
- Action: a choice made by the agent.
- Reward: a scalar feedback after an action.
- Policy: the rule by which the agent chooses actions.

**Objective**
- Maximize the expected cumulative discounted reward (the return), with discount factor $\gamma \in [0, 1]$ (see [[Expectation]]):
$$\mathbb{E}\left[\sum_{t=0}^{\infty} \gamma^t\, r_t\right]$$

**Properties**
- The signal is evaluative: it says how good an action was, not which action was correct.
- The reward can be delayed relative to the actions that caused it.
- The agent must trade off trying new actions (exploration) against using known good ones (exploitation).

**Comparison**
- [[Supervised Learning]] provides the correct answer through labels.
