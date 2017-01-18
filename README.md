# RL-Game-Bot
Using `Q learning`, a type of Reinforcement Learning to make a simple `GameBot`.

---------------------------------------------------
##Overview

This bot is an example of a type of [reinforcement learning](https://en.wikipedia.org/wiki/Reinforcement_learning) called [Q learning](https://en.wikipedia.org/wiki/Q-learning). 

	● Rules: The agent (yellow box) has to reach one of the goals to end the game (green or red cell).
	● Rewards: Each step gives a negative reward of -0.04. The red cell gives a negative reward of -1. The green one gives a positive reward of +1.
	● States: Each cell is a state the agent can be.
	● Actions: There are only 4 actions. Up, Down, Right, Left.

Here is the screenshot of the game -
------------------------------------
![Alt text](/game_world.JPG "Gaming environment.")

##Dependencies

None! Native Python

##Usage

Run `python Learner.py` in terminal to see the the bot in action. It'll find the optimal strategy pretty fast (like in `15 seconds`)