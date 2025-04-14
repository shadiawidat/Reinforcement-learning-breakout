# 🎮 Deep Reinforcement Learning for Breakout  
**Training an AI agent for Atari Breakout using Deep Q-Networks (DQN)**

---

## 📘 Project Overview

This project applies **Deep Q-Learning (DQN)** to train an agent to play **Atari Breakout** using only raw pixel inputs. The agent learns to maximize score through trial and error, using techniques like experience replay and a target network to stabilize learning.

Training was conducted in **Google Colab** using a **T4 GPU**, with model checkpoints saved every 1,000 episodes. Final results are visualized with reward plots and a gameplay video showing the trained agent in action.

---

## 🎯 Objectives

- Developed a reinforcement learning agent capable of playing Breakout autonomously.
- Implemented and trained a **Deep Q-Network (DQN)** using image-based state inputs.
- Visualized training performance over time.
- Evaluated the agent’s behavior via recorded gameplay.

---

## 🚀 Key Features

- ✅ **Deep Q-Learning implementation** from scratch using TensorFlow/Keras
- 🧠 **Convolutional Neural Network (CNN)** for processing image frames
- 🔁 **Experience Replay** and **Target Network** for training stability
- 💾 **Model checkpointing** to resume and continue training
- 📈 **Reward tracking** and training visualization
- 🎥 **Gameplay video generation** for qualitative evaluation

---

## 🧰 Technologies Used

- **Python 3.10+**
- **TensorFlow / Keras**
- **OpenAI Gym** (`Breakout-v0`)
- **NumPy**, **Matplotlib**
- **Google Colab** (GPU runtime)

---

## 📊 Training Results

- Trained over **32,000 episodes**
- Demonstrated consistent improvement in game performance
- Agent learned key strategies such as maintaining ball control and aiming for high-reward areas
- Training metrics (e.g., rewards per episode) visualized throughout the learning process

> ⚠️ Note: Training was interrupted due to runtime limitations on Colab but successfully resumed from saved checkpoints.

---

## 🎬 Video

![breakout-vedio](https://github.com/user-attachments/assets/43c3efd8-5b30-4367-8b83-a46019fe7a8d)

---


