# CS-370: Pirate Intelligent Agent – Portfolio Reflection  
**Author:** Laura Malone  
**Course:** CS-370 Current & Emerging Trends in Computer Science  
**Instructor:** Mohammad Habibi  
**Date:** October 2025  

---

## 📘 Project Overview  
This project focuses on developing an **intelligent pirate agent** that learns to navigate a maze and locate hidden treasure before the human player. The agent uses **deep Q-learning**, a reinforcement learning algorithm where decisions are improved through feedback from previous actions.  

The base code provided included:
- The **maze environment** and rendering logic  
- A starter **agent framework** with placeholders for learning and decision-making  
- A **training pipeline** outline without a complete implementation  

From there, I implemented and customized several key features:  
- Completed the **Q-learning training loop (`qtrain`)** with replay memory and epsilon-greedy exploration  
- Designed the **neural network model** using Keras to approximate the Q-function  
- Tuned hyperparameters for improved convergence, such as epsilon decay, learning rate, and batch size  
- Modified maze states and environment conditions to test adaptability  
- Logged and evaluated model performance during training  

These additions allowed the pirate agent to progressively learn optimal paths through exploration and reinforcement, ultimately achieving strong performance in finding treasure efficiently.

---

## 🧠 Connecting Learning to Computer Science  

### What Do Computer Scientists Do and Why Does It Matter?  
Computer scientists solve real-world problems using algorithms, data structures, and intelligent systems. They analyze patterns, automate processes, and create scalable solutions that drive innovation. The work matters because it underpins the **technology ecosystem**—from AI-driven automation to cybersecurity defense and beyond.  

Projects like the pirate agent show how **computational models of learning** can simulate intelligent behavior, supporting advances in fields such as **autonomous robotics, natural language processing, and decision-making systems**.

---

### How Do I Approach a Problem as a Computer Scientist?  
I approach problems through a structured, iterative process:  

1. **Analyze the problem** – Identify the system goals, rules, and constraints.  
2. **Model the solution** – Break down the logic into code and design algorithms to simulate intelligent behavior.  
3. **Implement and test** – Develop, train, and refine using feedback and metrics.  
4. **Iterate and optimize** – Continuously adjust model parameters, review data flow, and validate results.  

This approach reflects the **scientific method in software form**—hypothesis, experiment, and refinement—which is central to how computer scientists design reliable and adaptive systems.

---

### What Are My Ethical Responsibilities to the End User and the Organization?  
Ethics are essential in artificial intelligence and computer science. A responsible computer scientist must:  
- **Ensure fairness and transparency** in data-driven decision-making  
- **Protect user privacy and data integrity**  
- **Avoid harm** by testing systems for unintended consequences  
- **Design with accountability**, ensuring results can be explained and validated  

Within an organization, these ethical practices build **trust and sustainability**. For the end user, they provide confidence that intelligent systems behave predictably, safely, and in alignment with intended goals.

---

## 🪙 Reflection  
Developing the pirate intelligent agent was both challenging and rewarding. Early on, I struggled with hyperparameter tuning and balancing exploration with exploitation, but those frustrations became valuable lessons in patience and iteration. Watching the model’s performance improve reinforced my understanding of **how reinforcement learning mimics human trial and error**.

This project deepened my appreciation for **machine learning’s adaptability** and how even simple agents can demonstrate complex decision-making behaviors. It also mirrored the broader computer science process—constant experimentation, problem decomposition, and refinement toward an optimized solution.  

Ultimately, this project taught me not just how to train a model, but how to think like one: to learn from failure, adjust strategy, and pursue improvement through continuous feedback.

---

## 🧾 References  
- Gulli, A., & Pal, S. (2017). *Deep Learning with Keras.* Packt Publishing.  
- Beysolow II, Y. (2018). *Applied Reinforcement Learning with Python.* Apress.  

This repository contains:  
- `pirate_agent.ipynb` — The Jupyter Notebook implementing the deep Q-learning pirate agent
- `Design Defense` — Design Defense for Pirate Intelligent Agent
- `README.md` — This reflection file detailing project work, learning connections, and ethical context  

---
