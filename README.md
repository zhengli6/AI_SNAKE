
Apply a reinforcement learning to SNAKE

This project is written in Python

SNAKE is a classic video game that originated from the concept where the player maneuvers a line which grows in length, with the line itself being a primary obstacle. In the game, the trail grows longer as the player acquire more food in the plane, the game becomes progressively more difficult because the player has to avoid both plane boundary and snake itself. This term project aims to develop an artificial agent that plays SNAKE using the Q-learning algorithm. This project adapts relative quadrant to represent the whole game state which significantly improves the computational cost. The final result shows that the algorithm converges at 1000 learning games with reduced state- action domain and the trained agent is able to capture more than 20 food items in a 10x10 plane board. It is very crucial to choose efficient state space when performs reinforce learning as the size of state space directly affects the efficiency of the learning process. For more details, please see [CS440 report](CS440_Project_paper.pdf)
