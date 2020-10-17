# Unity-RL-Maze
Reinforcement learning is an important machine learning method, an online
learning technology where an action determined by the policy is rewarded with
an appraisal. The intelligent agent improvises its action strategy to adapt to the
environment based on the appropriate appraisal obtained from the actions deter-
mined. In recent years, a family of policy gradient methods for reinforcement
learning was introduced which perform one gradient update per data sample
and were relatively complicated to understand and implement. Therefore, a
much simpler RL algorithm, which is Proximal Policy Optimization(PPO)
was invented, that strikes a perfect balance between the ease of implementation,
sample efficiency, and ease of tuning.
In this project, we solved a simple maze game wherein the agent was trained
to and the shortest path towards the target with minimal collisions with the
walls and the obstacles. Unity 3D - a game development platform is used
for creating a maze-like environment. ML-agents toolkit, an open-source Unity
project is used, which enables the training of the intelligent agents using reinforcement learning or any machine learning methods through a simple-to-use
Python API.
Then different features of the Unity were utilized to analyze and monitor
the performance of the policy optimization e.g. multiple environment spaces
were built, creating replicas of the same environment to monitor the speed
of convergence while parallel training, played with the Curriculum learning,
shaping the rewards i.e. finding the right amount of reward that needs to be
assigned for each state-action pair, tweaking the parameters for Ray-perception
3D sensor for the agent and finally gathering the results and analyze the
training statistics with the plots.