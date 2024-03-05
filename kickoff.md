Meeting summary:
1. Discuss Unity vs Unreal in-engine machine learning components.
2. Bio data: eye tracking, gaze, head position data.
3. Behavioral data: any interaction with environment, e.g. grabbing an object, how fast a user was able to read the manual and follow it, etc.
4. What bio and behavioral data can be used for education?
5. For now, only talk about models that utilize available data.
6. If something doesn't work, we can define a custom model that will use new additional data.

# Comparison of Unity and Unreal Engine in-engine Machine Learning Based Components

## Unity

1. ML-Agents (reinforcement learning): Unity's ML-Agents toolkit allows developers to incorporate machine learning into virtual reality environments for training intelligent agents. This framework enables the creation of complex behaviors and interactions within VR simulations.

2. Perception (computer vision & synthetic data generation): Unity provides perception packages that include pre-trained machine learning models for tasks such as object detection, segmentation, and pose estimation. These models can enhance the visual perception capabilities of VR applications, enabling more immersive experiences.

3. TensorFlowSharp: Unity supports TensorFlowSharp, which enables integration with TensorFlow models directly within Unity projects. This opens up possibilities for leveraging a wide range of machine learning models for VR development, including those trained for tasks such as natural language processing or image recognition.

4. Custom models.

## Unreal Engine

1. UE4 Built-in AI Framework: Unreal Engine provides a built-in AI framework that includes functionalities for implementing machine learning algorithms such as behavior trees, blackboards, and perception systems. Developers can leverage these tools to create intelligent NPCs and virtual characters with adaptive behaviors in VR environments.

2. Third-Party Plugins: Unreal Engine supports integration with third-party machine learning plugins and libraries. For example, developers can use plugins like TensorFlow for Unreal Engine to incorporate TensorFlow models directly into their VR projects. This allows for a wide range of machine learning applications, including object detection, natural language processing, and gesture recognition within Unreal Engine VR experiences.

3. Custom Integration: Similar to Unity, developers can implement custom machine learning algorithms and models within Unreal Engine using C++ or Blueprint scripting. By interfacing with external machine learning frameworks or implementing algorithms from scratch, developers have the flexibility to incorporate machine learning into their VR projects to enhance interaction, perception, and intelligence.

4. Unreal Engine Marketplace: The Unreal Engine Marketplace offers a variety of AI and machine learning assets, including pre-trained models, example projects, and tools for integrating machine learning into VR experiences. Developers can explore these resources to accelerate the development process and add advanced AI capabilities to their VR projects.

# Possible Educational Environments

Here we discuss educational environments that might make use of in-engine ML components:
1. Analyze user eye data (focused, bored): I see you are too focus, keep thinking. I see you are bored, let us try another topic? Give use multiple topics, puzzles, analyze user data (how confused they are, analyze eye data) and see which topic he likes more (since some people do not really know what they like). 
2. Continuing with previous example, the game can adapt based on user behavioral data to give different problems/easier problems. E.g. the size of the hole where you put an object gets bigger. Or if the person takes too many tries, you remove some components that make the game difficult.
3. Narator talks about something. If user frowns, narator says: "Oh, I see you are confused. Let me explain it in more detail.".
4. P#rn: based on eye data, can feed more of the places where a person looks at, switch camera, change avatars: prefered body types, voice.
