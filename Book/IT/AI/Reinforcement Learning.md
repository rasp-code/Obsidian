---
created: 2026-09-11
updated: 2026-09-14
---
MDP = Markov Decision Process:
- a set of states
- a set of possible actions
- transition probabilities 
- a reward function
- usually a discount factor $\gamma$ ($\in [0; 1]$, the closer to 1 the more the future is considered)

V(s) = state-value function, quality of a state considering the future gains with the current politic
Q(s, a) = action-value function, quality of an action considering the future gains with the current politic

The Multi-Armed Bandit Problem ("les bandits manchots" in french) = a category of problem in which the player has to choose actions hopping for rewards and where the exploitation vs exploration dilemma is central.