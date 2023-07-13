# Inverted_pendulum

This repository contains the Reinforcement learning agents that have been used to solve the inverted pendulum problem and the urdf file used to create the pendulum

## Problem :- 
We are presented with the pendulum which is initially in its stable position, i.e. facing downwards with no velocity.<br>
We are tasked to bring the pendulum to its upright position:-<br>
i. By applying torque in the range -0.15 to 0.15 to the pendulum. (Continous Action space).<br>
ii. By applying either -0.15 or 0.15 or no force at all to the pendulum (Discrete Action Space).

## Agents used :-
i. Deep Deterministic Policy Gradient (DDPG) is used for Continous action space.<br>
ii. Deep Q Network (DQN) and Double Deep Q Network (DDQN) is used for Discrete action space.

## Result :-
Except for DQN the other agents were able to make the pendulum in a nearly stable upright position.
