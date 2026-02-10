# Lab 3: Contextual Bandit-Based News Recommendation System

**Student:** Aman | **Roll Number:** U20230054

## Lab Report

This project implements a contextual multi-armed bandit (CMAB) framework for personalized news recommendations. A Random Forest classifier achieved 90% validation accuracy in predicting user categories (user_1, user_2, user_3). Three bandit algorithms were evaluated over 10,000 simulation steps: Epsilon-Greedy (avg reward: 5.67), SoftMax (5.83), and UCB (5.98). UCB demonstrated superior performance through principled uncertainty-based exploration. The complete system integrates user classification, bandit-based category selection, and article sampling. All algorithms successfully learned context-specific preferences, with comprehensive visualizations showing convergence patterns across user contexts. The implementation validates CMAB effectiveness for adaptive content recommendation systems.

---

**Key Results:**
- **Classification Accuracy:** 90.00% (Random Forest)
- **Best Algorithm:** UCB (c=2.0) with average reward of 5.9770
- **Simulations:** 10,000 steps per algorithm

