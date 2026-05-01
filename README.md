# Autonomous-AI-Robotics-Research
Empirical studies in Reinforcement Learning (Q-Learning, SARSA, DQN) and Multi-Modal CNNs for autonomous robotic systems.

This repository contains a collection of empirical studies and implementations focused on Reinforcement Learning (RL), Computer Vision, and Multi-Agent systems developed during my MSc in Aerial Robotics at the University of Bristol.

## 🔬 Core Projects

### 1. Reinforcement Learning Baselines (`AI_PartB.py`)
*   **Implementation:** Tabular Temporal Difference (TD) learning including **Q-Learning** and **SARSA**[cite: 11].
*   **Objective:** Comparative analysis of convergence rates and policy stability in discrete grid-world environments[cite: 11].

### 2. Deep Reinforcement Learning (`AI_PartC_task2&3.py`)
*   **Implementation:** **Deep Q-Network (DQN)** using TensorFlow and OpenAI Gym[cite: 13].
*   **Focus:** Navigating complex maze environments with dynamic obstacles and sparse reward structures[cite: 13].

### 3. Multi-Modal Representation Learning (`AI_PartC_Task1.py`)
*   **Architecture:** Fused **Convolutional Neural Network (CNN)** and Dense sensor-processing branch[cite: 14].
*   **Goal:** Predicting agent "flight" capabilities by merging 80x80 RGB imagery with numerical sensor telemetry[cite: 14].

### 4. Supervised & Unsupervised Learning (`AI_PartA.py`)
*   **Techniques:** K-Means clustering, GMM, Decision Trees, and Logistic Regression[cite: 12].
*   **Application:** Baseline performance benchmarking for robot classification and bribe-amount regression tasks[cite: 12].

## 🛠️ Requirements
*   Python 3.x
*   TensorFlow
*   NumPy
*   Scikit-learn
*   Gym
