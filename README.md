1)State Estimation of an Autonomous Agent 
- Discrete Space Case: Used Hidden Markov Model to estimate agent’s current location (using Bayes Filter
algorithm), past locations (using Smoothing), future locations and most-likely path (using Viterbi algorithm)
- Continuous Space Case: Implemented Kalman Filter algorithm to estimate state of the agent under sinusoidal
control policy; implemented Global Nearest Neighbour Filter for data association in multi-agent environment

2)Motion Planning under uncertainty 
- Simulated navigation of an autonomous agent in grid world domain with stochastic actions and single goal state
- Formulated the problem as a Markov Decision Process and implemented Value Iteration to find optimal policy
- Implemented Q-Learning (Model-Free RL) to find a good policy when transition & reward functions are absent


Course Webpage: https://www.cse.iitd.ac.in/~rohanpaul/teaching/2021-col864.html
