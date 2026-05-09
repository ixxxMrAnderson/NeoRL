# Exploring NeoRL

[View the paper](main.pdf)

## Abstract

Offline reinforcement learning (RL), also known as batch RL, offers the prospect of policy optimization from large pre-recorded datasets without online environment interaction. Based on the NeoRL benchmark, we apply a novel offline RL algorithm to learn policies from stock data using a form of critic-regularized regression, named CRR. Considering the finance setting, we provide the agent not only the current observation but also historical data, which we call "CRR with Past", and find that this feature is essential in improving performance. What's more, we compare several variants of CRR and discuss the choice of different weight functions.
