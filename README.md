# 🐟 Fish Classification and Smart Navigation System

This project integrates *Computer Vision, **Reinforcement Learning, and **Markov Models* to classify fish species and navigate a dynamic environment using intelligent agents. It demonstrates a powerful combination of machine learning models working together in a simulated or real-time system.

---

## 🚀 Technologies Used

•⁠  ⁠*Convolutional Neural Network (CNN)*  
  MobileNetV2 is used for lightweight and accurate fish classification from images.

•⁠  ⁠*Q-Learning*  
  Reinforcement learning algorithm used to guide multiple agents through a dynamic environment with changing obstacles.

•⁠  ⁠*Markov Model*  
  A probabilistic model used for predicting state transitions within the environment or fish movement.

---

## 🧠 Project Architecture

### 1. Fish Classifier (CNN using MobileNetV2)
•⁠  ⁠Trained on a dataset of labeled fish images.
•⁠  ⁠Outputs the predicted fish species.
•⁠  ⁠Optimized for real-time inference on constrained hardware.

### 2. Multi-Agent Q-Learning
•⁠  ⁠Each agent maintains its own Q-table.
•⁠  ⁠The environment is represented as a grid with target and dynamic obstacles.
•⁠  ⁠Agents learn optimal policies to reach the goal without collisions.

### 3. Markov Model for State Transitions
•⁠  ⁠Defines the probabilistic transitions between environment states.
•⁠  ⁠Helps agents anticipate obstacle or fish movement and adapt their strategy.

---

## 📊 System Flow

```plaintext
1.⁠ ⁠Capture Image ➜ 2. CNN Classifies Fish ➜ 3. Markov Model Predicts State ➜ 
4.⁠ ⁠Q-Learning Agents Navigate Environment