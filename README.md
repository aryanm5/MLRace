# milestone-4-aryanm5
milestone-4-aryanm5 created by GitHub Classroom

# Milestone 4 Explanation
by Aryan Mittal

The moving circle with the arrow is called the **agent**.
The dark green circle is the **target**.

The agent uses **Reinforcement Learning**, which is a type of machine learning, to get to the target as fast as possible.

With Reinforcement Learning, the agent receives a state and a corresponding reward. The state is the state of the simulation, which is the location of each circle and the velocity of the agent.

The reward is calculated based on the agent's distance to the target. The closer the agent is to the target, the higher the reward. If the agent touches the target, it will gain 1 point and receive a large reward.

The agent learns over time as it collects more data that reaching the target first is good, and will act accordingly to get the maximum reward.

The brown circle does not use machine learning to move. Its instructions are hardcoded to simply move in the direction of the target, so it does not improve.

When the simulation starts, the brown circle is generally much more consistent and reaches the target first most of the time. The agent's moves are mostly random as it explores the simulation and gathers data. However, if you let the simulation run for a while, the machine learning agent will start improving exponentially until it is reaching first almost every time. The harcoded ball's performance stays mostly linear and does not catch up to the machine learning ball.

Progress of the simulation can be observed through the line graph below the simulation, which shows the number of points that each player has and updates every 5 seconds.

The lesson from this experiment is that machine learning and hardcoded instructions perform best under different conditions. Machine learning greatly outperforms hardcoded instructions once enough data is collected. However, without large amounts of data, machine learning is not reliable or "smart", and shouldn't be used.

![Image of graph after enough time has passed](graph_long.png?raw=true "Graph after enough time has passed")
