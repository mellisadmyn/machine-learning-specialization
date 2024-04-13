## Reinforcement Learning

### What is Reinforcement Learning?

- Reinforcement learning uses a reward function to tell the algorithm when it's doing well and when it's doing poorly.
- The reward function is like training a dog - rewarding good behavior and discouraging bad behavior.
- The key idea of reinforcement learning is to specify a reward function instead of the optimal action, giving flexibility in system design.
- The state, action, reward, and next state are core elements in reinforcement learning algorithms.

### The Return in reinforcement learning

- The return in reinforcement learning captures the idea of comparing different sets of rewards.
- The return is the sum of the rewards, weighted by a discount factor.
- The discount factor is a number slightly less than 1, which determines the importance of future rewards.
- Rewards that are obtained sooner are given more credit in the return calculation.
- The discount factor can be thought of as the interest rate or time value of money in financial applications.
- The return depends on the actions taken and the rewards obtained in different states.
- Different actions can lead to different returns from different states.
- Negative rewards incentivize the system to push them further into the future.