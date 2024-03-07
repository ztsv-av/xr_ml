### Reinforcement Learning (RL):

- Environment: The house, with obstacles like furniture and dirt patches.
- Agent: The robot vacuum cleaner.
- Actions: Move forward, turn left, turn right, suck dirt.
- Reward: Positive reward for cleaning dirt, negative reward for bumping into furniture or getting stuck.

### Q-learning:

- The robot starts by exploring the house randomly, taking different actions and observing the rewards it receives.
- It keeps track of a Q-table, which stores the estimated Q-value (future reward) for each combination of state (e.g., location in the house) and action (e.g., move forward).
- Each time the robot takes an action and receives a reward, it updates the corresponding Q-value in the Q-table using a learning rule. This rule considers the immediate reward, the estimated future reward from the new state, and the previous Q-value.
- Over time, through exploration and learning, the robot gradually learns which actions in different locations of the house (states) lead to higher future rewards (cleaning efficiently).
- Eventually, the robot can choose the best action (e.g., move towards dirt) in any state based on its learned Q-values, enabling efficient cleaning.
