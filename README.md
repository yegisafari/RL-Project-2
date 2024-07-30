# RL-Project-2
## Reinforcement-learning-RL-Project-2

Hi there! In this project, I explored a 5x5 gridworld environment using Q-Learning, a popular reinforcement learning algorithm. The gridworld has 25 states, and the agent can move up, down, left, or right. Special states offer different rewards, influencing the agent's behavior.

### What's Inside

**Q-Learning** : I used this algorithm to learn optimal policies by updating the action-value function based on rewards and transitions.

**Simple Gridworld** : A basic environment to demonstrate Q-Learning.

**Modified Gridworld** : An environment with terminal states (black squares) for more complex scenarios.

### How Q-Learning Works
### Formula:

Q(s,a)←Q(s,a)+α[r+γmaxa′Q(s′,a′) − Q(s,a)]
* Q(s,a): Q-value for state s and action a
* α: Learning rate
* r: Reward received
* γ: Discount factor
* maxa′Q(s′,a′) : Max Q-value for next state s′

### Environment Setup
### Special States and Rewards

**Blue** : Any action yields a reward of 5 and jumps to Red.

**Green** : Any action yields a reward of 2.5 and jumps to Yellow or Red with a probability of 0.5.

**Red** : Terminal state.

**Yellow** : Terminal state.

**Black** : Terminal states added in the modified gridworld.

### Rewards

Moving to another white square: -0.2

Moving off the grid: -0.5

### Doing this Project I got help from:

1. The class lectures content
2. YouTube
3. These websites:

(https://gurpreet-ai.github.io/policy-evaluation-deep-reinforcement-learning-series/)

(https://medium.com/@edu.pignatelli/iterative-policy-evaluation-33056f3f21a4)

