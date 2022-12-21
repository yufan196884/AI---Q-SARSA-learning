# AI---Q-SARSA-learning

For a class project.

Implemented 2 reinforcement learning algorithms (Q learning and SARSA learning) for a simple learning task. They are part of the same family of algorithms known as temporal difference learning. The general idea is as follows:

1. Discretize time into small, fixed duration blocks.
2. For each time block, perform an action according to some policy and record the reward received, given by some reward function defined by the environment. ('Policy' is a rulebook that decides what action the agent takes at each state.)
3. Update the policy according to an algorithm (Q and SARSA learning employs different algorithms here) 
4. Eventually, the  policy will converge and stop changing, due to Banach Fixed Point Theorem. The rate at which it converges depends on model parameters.
5. Return this policy.
