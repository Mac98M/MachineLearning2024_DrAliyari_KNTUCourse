This folder contains the implementations of the Q-learning and DQN algorithms tailored for the Wumpus World problem. Both implementations include essential components such as the environment setup, agent training, and performance evaluation.

The Q-learning implementation involves a grid-based environment where the agent updates its Q-values based on the state-action-reward-next state transitions. The Q-learning agent starts with an exploration phase to gather information about the environment and gradually shifts towards exploitation as it learns the optimal policy. Key hyperparameters such as the learning rate, discount factor, and exploration rate are fine-tuned to ensure efficient learning.

The DQN implementation leverages deep neural networks to approximate the Q-values, making it suitable for environments with larger state spaces. The DQN agent uses experience replay to store past experiences in a buffer and samples from it to update the Q-network, breaking the correlation between consecutive experiences. A target network is used to provide stable Q-value updates, addressing the moving target issue inherent in reinforcement learning. The implementation also includes the necessary components for training the neural network, such as the loss function, optimizer, and training loop.

Both implementations include scripts for training the agents and visualizing their performance. The training scripts allow you to specify hyperparameters and track the agent's learning progress through plots of total rewards, cumulative rewards, and mean rewards per episode. Additionally, the implementations are designed to be modular and extensible, allowing for easy modification and experimentation with different settings and environments.

This project demonstrates the application of reinforcement learning algorithms to a classic AI problem, highlighting the practical aspects of training agents to make optimal decisions in uncertain environments. The code provided serves as a foundation for further exploration and experimentation in the field of reinforcement learning.

Feel free to explore the Code folder, run the training scripts, and visualize the results to gain a deeper understanding of how Q-learning and DQN can be applied to solve complex decision-making problems like the Wumpus World.


Google Colab file link address :

Q1 : https://colab.research.google.com/drive/1JLMGpxVqUsESdC5bmv61DCmySJ4HSUvi?usp=sharing
