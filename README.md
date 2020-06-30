# milestone-4-aryanm5
milestone-4-aryanm5 created by GitHub Classroom

#Milestone 4

by Aryan Mittal

Explanation:

The moving circle with the arrow is the agent.

The agent uses Reinforcement Learning, which is a type of machine learning, to learn to stay as close as possible to the dark green circle but stay outside the red circle at all costs.

With Reinforcement Learning, the agent receives a state and a corresponding reward. The state is the state of the simulation, which is the location of each circle.

The reward is calculated based on the agent's distance to the green circle and red circle. If the agent is inside the red circle, the reward will be negative depending on how close the agent is to the center of the red circle.

If the agent is outside the red circle, the reward will be positive depending on how close the agent is to the green circle.

The agent learns over time as it collects more data that being close to the green circle is good, while being in the red circle is bad, and will act accordingly to get the maximum reward.

The red circle does not use machine learning to move. Its instructions are hardcoded, so it does not improve.

If you let the simulation run for some time, you can observe that the agent is much better than before.

The lesson from this experiment is that machine learning greatly outperforms hardcoded instructions if enough data is present. However, without large amounts of data, machine learning is not reliable or "smart".
