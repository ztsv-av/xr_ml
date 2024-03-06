Meeting summary:
1. Discuss Unity vs Unreal in-engine machine learning components.
2. Bio data: eye tracking, gaze, head position data.
3. Behavioral data: any interaction with environment, e.g. grabbing an object, how fast a user was able to read the manual and follow it, etc.
4. What bio and behavioral data can be used for education?
5. For now, only talk about models that utilize available data.
6. If something doesn't work, we can define a custom model that will use new additional data.

# Comparison of Unity and Unreal Engine in-engine Machine Learning Based Components

## Unity ML-Agents

Reinforcement learning - where agents learn through trial and error by receiving rewards for desired actions.

### Workflow:

1. Environment Setup: Develop your VR scene in Unity, including objects, interactions, and the desired behavior of the AI agent.
2. Agent Creation: Utilize the ML-Agents toolkit to define the agent. This involves specifying the agent's sensors (e.g., camera, raycast for object detection) and available actions (e.g., move, look, interact).
3. Reward System: Design a reward system that incentivizes the agent's desired behaviors. This could involve rewards for completing tasks, interacting with specific objects, or exploring the environment efficiently.
4. Training Process: Run the simulation and let the ML-Agents framework train the agent through trial and error. The agent will explore the environment, take actions based on its sensors, and receive rewards or penalties based on the defined system. As training progresses, the agent's decision-making improves, allowing it to achieve the desired goals.

## Unreal Engine - Learning Agents

Offers both **reinforcement learning** and **imitation learning**. In imitation learning, agents learn by observing and mimicking the behavior of expert demonstrations.

Experimental plugin.

# Possible Educational Environments

Here we discuss educational environments that might make use of in-engine ML components:
1. Analyze user eye data (focused, bored): I see you are too focus, keep thinking. I see you are bored, let us try another topic? Give use multiple topics, puzzles, analyze user data (how confused they are, analyze eye data) and see which topic he likes more (since some people do not really know what they like). 
2. Continuing with previous example, the game can adapt based on user behavioral data to give different problems/easier problems. E.g. the size of the hole where you put an object gets bigger. Or if the person takes too many tries, you remove some components that make the game difficult.
3. Narator talks about something. If user frowns, narator says: "Oh, I see you are confused. Let me explain it in more detail.".
