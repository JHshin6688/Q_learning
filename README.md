# Reinforcement_Learning-Q-learning
The purpose of this project is to implement a Q-learning framework to train the agent on SlipperyFrozenLake, which is modified from the FrozenLake provided in gym library. The rules are provided as follows:

1. The agent starts in the starting point (S), and the goal is to reach the goal (G) while avoiding the holes (H).
2. The agent can choose four actions: Left (0), Down (1), Right (2), Up (3)
3. If the agent choose one action, the agent moves toward the selected direction until one of the condition is satisfied.
4. The agent stops if the rock (R) blocks the agent.
5. The agent stops if the agent reaches the boundary of the lake.
6. The agent stops if the agent meets the hole (H). This is the case that we should avoid.
7. The agent stops if the agent reaches the goal (G). This is the case that we want.
