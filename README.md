# 🎮 AI & Games: The Evolution of Machine Learning in Board Games

Welcome to our Connect 4 AI Project!  
This repository showcases an end-to-end machine learning pipeline that trains AI models—Convolutional Neural Networks (CNNs) and Transformers—to play Connect 4. It also includes deployment using Docker, AWS Lightsail, and a fully interactive Anvil web application.

🕹️ **[Play the Game Here](https://tremendous-tempting-analyst.anvil.app/)**

---

## 🧠 Why Teach AI to Play Games?

Games offer structured environments with clear outcomes, making them ideal testing grounds for AI decision-making. Techniques developed for games—like MCTS and deep learning—translate into real-world use cases in self-driving cars, finance, and healthcare.

## 🧩 Why Connect 4?

- Balanced complexity (more advanced than Tic-Tac-Toe, simpler than Go)
- A solved game, perfect for testing learning from data vs. rules
- Spatial and strategic depth ideal for CNNs and Transformers

---

## 🔍 Project Objectives

- Can a neural network mimic MCTS gameplay strategies?
- How do CNNs compare to Transformers in pattern recognition?
- Can deep learning independently learn game-winning tactics?

---

## 🔄 Workflow Overview

### 1. **Data Generation (MCTS Self-Play)**
- Generated board states and optimal moves using MCTS
- Randomized move strength and variability to diversify data
- Handled board flipping to maintain player perspective balance

### 2. **Model Development**
#### CNN
- 10-layer architecture with 2-channel input
- Used dropout, L2 regularization, global avg pooling
- Achieved **~69% accuracy** and strong real-world performance

#### Transformer
- Vision Transformer architecture
- Positional embeddings & attention layers
- Achieved **~58% accuracy**, slower and less structured gameplay

### 3. **Deployment**
- Dockerized model with all dependencies and trained weights
- Hosted on **AWS Lightsail**
- Frontend created using **Anvil** with live board updates via Matplotlib

---

## 📊 Key Results

| Model      | Training Acc | Validation Acc | Test Acc | Real-Time Gameplay |
|------------|--------------|----------------|----------|---------------------|
| CNN        | 69.81%       | 64.85%         | 66.50%   | Strong strategist, hard to beat |
| Transformer| 61.54%       | 58.00%         | 58.19%   | Defensive, less aggressive |

---

## 🖥️ Frontend & UX

- Developed using **Anvil** with **Matplotlib** visualizations
- Fully interactive gameplay
- Dynamic updates rendered in-browser from server-side AI decisions

---

## 🚀 Future Work

- Explore Reinforcement Learning (e.g., Deep Q-Networks, AlphaZero)
- Expand to more complex games like Go or Chess
- Introduce user login and tracking to gather diverse gameplay data
- Adaptive AI models that learn from user interactions over time

---

## 📚 References

- [Game Playing in Artificial Intelligence](https://en.wikipedia.org/wiki/Game_playing_(artificial_intelligence))
- [The Intersection of Video Games and AI – NVIDIA](https://blogs.nvidia.com/)
- [Applying Machine Learning to Connect Four](https://towardsdatascience.com/)

---

## 🙌 Project Team

- **Arantza Garcia Delfin** 
- **Biagio Alessandrello** 
- **Sneha Sastry Rayadurgam**
- **Utkarsh Garg** 

---

Thank you for reading our blog and exploring our Connect 4 AI!  
Let the games begin 🎲
