# Fall 2022 Hackathon
# Name: Srinivas Rahul
# Title: Minimizing Costs in Energy Consumption of a Data Center

```
Individual Submission
```

## Motivation and Significance
<br/>DeepMind AI reduced Google's Data Center Cooling Bill by 40% in 2016 using their DQN AI model (Deep Q-Learning).
In this project, I will do something similar. I will design my server environment and an AI that will handle the
cooling/heating of the server so that it stays in an appropriate temperature range while conserving the most energy
and minimizing expenditures. Moreover, like DeepMind AI, my goal will be to save at least 40% of the power.
<br/>	

## Problem Statement<br/>
Minimizing Costs in Energy Consumption of a Data Center<br/>

## Reinforcement Learning Environment<br/>

- Reinforcement learning is training machine learning models to make a series of judgments. The agent learns how to
achieve a goal in an unpredictable, potentially complex environment. In reinforcement learning, artificial intelligence
is in a game-like setting, and the computer uses the trial-and-error method to solve this problem. AI is rewarded or
punished for the acts it does, and its purpose is to maximize the total reward.
- Although the designer establishes the reward policy—that is, the game rules—he provides no tips or suggestions to
the model on how to solve the game. It is up to the model to discover how to accomplish the task to maximize the
reward, beginning with random trials and progressing. Reinforcement learning is currently the most effective
technique to hint at computer creativity by utilizing the power of search and many trials. Unlike humans, artificial
intelligence can learn from thousands of parallel gameplays using reinforcement learning methods.
<br/>

###  Environment Variables<br/>
• Temperature of the server at any given moment
• Number of users on the server
• Rate of data transmission
• Energy spent by the AI on the server
• Energy spent by the server's integrated cooling system

## Deep Learning Neural Network <br/>
Source data from public data set on twitter dataset.<br/>

## Approach 
This implementation will be broken into five sections, where each section has its Python file. These five components
make up the generic AI Framework, or AI Blueprint, that should be followed whenever we create an environment to
tackle any challenge using Deep Reinforcement Learning.<br/>
- Step 1: Building the Environment.<br/>
- Step 2: Building the neural network.<br/>
- Step 3: DQN Implementation.<br/>
- Step 4: Training the network.<br/>
- Step 5: Testing the network.<br/>

## How to use<br>
### Dependencies
* [Instructions for installing openAI gym environment in Windows](https://towardsdatascience.com/how-to-install-openai-gym-in-a-windows-environment-338969e24d30)

### Training model for lunar lander environment<br>
git clone https://github.com/srsapireddy/cooling_data_center.git<br>
cd data_center/<br>
- Edit experiment parameters in train.py as needed<br>
python3 train.py<br>






