# Reinforcement-learning-specialization-Coursera 


The course focuses on “small-scale” problems in order to understand the foundations of Reinforcement Learning, as taught by world-renowned experts at the University of Alberta, Faculty of Science.

The tools learned in this Specialization can be applied to game development (AI), customer interaction (how a website interacts with customers), smart assistants, recommender systems, supply chain, industrial control, finance, oil & gas pipelines, industrial control systems, and more.

following is a brief description of each technique used in the module .

# 1. Dynamic Programming 
Consider a "GridWorld city" which is struggling with the city's street parking system which charges a fixed rate . The city council has created a Markov decision process (MDP) to model the demand for parking with a reward function that reflects its preferences.

states : nonnegative integers indicating how many parking spaces are occupied

action : nonnegative integers designating the price of street parking

reward : real value describing the city's preference for the situation

env : GridWorld city

objective : Determine the optimal policy for GridWorld city such that there's  atleast one spot  left unoccupied all the time (so that it is available in case someone really needs it)

# 2. Policy evaluation with temporal difference 
objective :To design an agent for policy evaluation in the "Cliff Walking environment". Recall that policy evaluation is the prediction problem where the goal is to accurately estimate the values of states given some policy. temporal difference algorithm is used for policy evaluation

env: A cliff walking gridworld with discrete state space and discrete action space.

action : Up, Down, Left or Right.

reward :  -1 reward per step , and -100 reward when falling off of the cliff.

termination occcurs when the agent reaches the goal . it is an "episodic task" 

# 3.  temporal difference learning for control
objective : comparing two algorithms Q-learning and expected sarsa with epsilon greedy action in order to determine the improved policy (optimal policy)

env: A cliff walking gridworld with discrete state space and discrete action space.

action : Up, Down, Left or Right.

reward :  -1 reward per step , and -100 reward when falling off of the cliff.

# 4. model based method Dyna Q and Dyna Q+ 
objective : To determine the shortcut path to the goal using model based method Dyna Q and Dyna Q+ on a " Maze environment "

env : Maze environment 

action : Up, Down, Left or Right.

reward :  +1 on reaching the goal state, 0 otherwise.

# 4. Semi-gradient TD with a Neural Network
objective : To solve a policy evaluation using Semi-gradient TD with a Neural Network (state value approximation)

state: 500 randomwalk (large state space )

action : left ,right

neuarl network i/p : one-hot encoding of the state number.

neural network o/p : estimated state value (single o/p value)

# 5 . solving Lunarlander 
objective : implementing an RL agent using nn for function approximation (action value)

neuarl network i/p : one-hot encoding of the state number.

neural network o/p : estimated state action value( no.of o/p= total no.of actions)
