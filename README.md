# AIAA3053 Reinforcement Learning Final Project

## Literature Research on Communication Methods of Multi-Agent Reinforcement Learning in Traffic Signal Control

**Authors**: Anqi ZHAO, Yichang LIU, Yingwen PENG

This repository contains the final project report for the course AIAA3053 Reinforcement Learning. The report provides a comparative literature survey on communication-based Multi-Agent Reinforcement Learning (MARL) methods applied to Traffic Signal Control (TSC).

## Overview

Efficient traffic signal control is critical for mitigating urban congestion and enhancing environmental sustainability. While deep reinforcement learning (DRL) has shown promise for adaptive signal timing, single-agent approaches struggle with the complex spatiotemporal dependencies of large-scale urban grids. Multi-agent reinforcement learning (MARL) provides a collaborative framework, but achieving network-wide optimization relies heavily on effective communication methods between agents.

This report analyzes one foundational review and four representative research articles, comparing their approaches to agent communication, coordination strategies, policy learning, and experimental results.

## Key Topics Covered

- Markov Decision Process (MDP) formulation for TSC
- Three communication paradigms: attention-based, selective, GNN-based, and group-based
- Evaluation of control performance, scalability, efficiency, and policy transferability
- Open challenges: simulation-to-real gap, benchmarking standards, robustness under partial observability

## Selected Papers Analyzed

1. **CoLight** – Attention-based communication with Graph Attention Networks (GAT)
2. **QRC-TSC** – Selective communication with value decomposition (Q-MIX)
3. **Decentralized GNN** – Graph neural network-based communication using bidirectional graphs
4. **CGB-MATSC** – Group-based regional agent abstraction and coordination

## File Structure
├── AIAA3053_Reinforcement_Learning_Final_Project_Report.pdf  
└── README.md
