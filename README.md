# Policy Optimization for Financial Decision-Making

This project explores the transition from traditional risk prediction to profit maximization in financial lending. Using the LendingClub dataset, we compare two distinct modeling paradigms:
1.  Supervised Deep Learning (DL): A classifier that predicts the probability of loan default (Risk Minimization).
2.  Offline Reinforcement Learning (RL): A Conservative Q-Learning (CQL) agent that learns a policy to maximize total portfolio value (Profit Maximization).

The goal is to demonstrate that an RL agent can intelligently approve "high-risk" loans if the associated interest rate offers sufficient reward to justify that risk.


This project was developed and trained in a Kaggle Notebook environment.
**Platform:** Kaggle Kernels
**Hardware Accelerator:** NVIDIA Tesla T4 GPU x2
**RAM:** 30 GB (High-RAM setting recommended for data loading)
**Environment:** Python 3.10 / Docker image `kaggle/python`

While the code can run on a CPU, training the Offline RL agent (CQL) is significantly faster on a GPU. If running locally, ensure you have CUDA installed.

