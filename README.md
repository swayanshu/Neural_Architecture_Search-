# Neural_Architecture_Search

Neural Architecture Search is a method that automates the process of designing neural network architectures. Instead of manually selecting and tweaking model structures, NAS algorithms search the space of possible network architectures to find the best-performing ones, often leading to highly optimized and efficient models.

## Why is NAS Important?
Manual design of deep learning models is time-consuming and suboptimal.
NAS helps in discovering architectures that are optimized for both accuracy and efficiency.
It can generate architectures better than manually crafted ones, as seen in Google’s EfficientNet and AmoebaNet. 

## 3 Core Components of NAS

1. Search Space
- Example: Number of layers, types of layers (Conv2D, Dense, LSTM), kernel sizes, activation functions.
2. Search Strategy
Common techniques:
- Random Search: Samples architectures randomly.
- Reinforcement Learning (RL): Uses an agent to learn optimal architectures via rewards.
- Evolutionary Algorithms: Uses genetic evolution to find better architectures over generations.
- Gradient-Based Methods: Optimizes architectures using continuous relaxation techniques (e.g., DARTS).
3. Performance Estimation
Methods:
- Training from Scratch: Train each model fully (expensive).
- Weight Sharing: Models share parameters to reduce computation time.
- Surrogate Models: Use proxy metrics (e.g., learning curve extrapolation) to predict performance.






