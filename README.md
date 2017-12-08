# Train-a-smart-cab-to-drive
Training a Smartcab to drive using Reinforcement learning
# Project Overview
In this project you will apply reinforcement learning techniques for a self-driving agent in a simplified world to aid it in effectively reaching its destinations in the allotted time. You will first investigate the environment the agent operates in by constructing a very basic driving implementation. Once your agent is successful at operating within the environment, you will then identify each possible state the agent can be in when considering such things as traffic lights and oncoming traffic at each intersection. With states identified, you will then implement a Q-Learning algorithm for the self-driving agent to guide the agent towards its destination within the allotted time. Finally, you will improve upon the Q-Learning algorithm to find the best configuration of learning and exploration factors to ensure the self-driving agent is reaching its destinations with consistently positive results.

#Install

This project requires Python 2.7 with the pygame library installed

#Code

The Q-learning code is provided in the smartcab/agent.py python file. Additional supporting python code can be found in smartcab/enviroment.py, smartcab/planner.py, and smartcab/simulator.py. Supporting images for the graphical user interface can be found in the images folder.

#Run

In a terminal or command window, navigate to the top-level project directory smartcab/ (that contains this README) and run one of the following commands:

python smartcab/agent.py python -m smartcab.agent

This will run the agent.py file and execute your agent code.
