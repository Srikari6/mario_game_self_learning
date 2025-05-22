#Mario_game_self_learning
Introducing a reinforcement learning
approach for playing the Mario game efficiently. We utilize
various reinforcement learning models, train them on Super
Mario, and evaluate their performance. Techniques like Proximal
Policy Optimization (PPO) and Deep Q-Network (DQN) are used
to develop RL-based decision-making. PPO Uses a policy network
to directly learn optimal actions but this algorithm requires
new interactions with the environment for each policy update.
Whereas DQN learns Q-values and derives a policy.Unlike PPO
(which is on-policy), DQN is off-policy, meaning it can reuse past
experiences stored in replay memory.
