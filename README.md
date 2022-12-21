# AI---Q-SARSA-learning

For a class project.

Implemented 2 reinforcement learning algorithms (Q learning and SARSA learning) for a simple learning task. They are part of the same family of algorithms known as temporal difference learning. The general idea is as follows:

Problem: 
An agent wants to achieve some goal in a hostile environment, and wants to incur the lowest possible penalty while doing so.

Solution:

Definition of terms:

reward function: A function defined by the environment that determines the reward/penalty for taking each action at each state.

Policy: A rulebook that the agent follows when deciding its action to take at each state.



1. Discretize time into small, fixed duration blocks.
2. For each time block, perform an action according to some policy and record the reward received, determined by the reward function.
3. Update the policy according using an algorithm (Q and SARSA learning employs different algorithms here) 
4. Eventually, the  policy will converge and stop changing, due to Banach Fixed Point Theorem. The rate at which it converges depends on model parameters.
5. Return this policy.
