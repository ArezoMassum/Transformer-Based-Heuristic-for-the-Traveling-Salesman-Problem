# Transformer-Based-Heuristic-for-the-Traveling-Salesman-Problem

## Overview
This repository implements a heuristic solution for the **Traveling Salesman Problem (TSP)** using **Transformer Models**. The goal is to explore the adaptability of transformers beyond NLP tasks and apply them to an NP-hard combinatorial optimization problem.

## Features

- **Dataset Handling**: Loads and preprocesses the TSP dataset, including training, validation, and testing sets.
- **Transformer-Based Model**: Implements a transformer encoder-decoder architecture adapted for solving TSP.
- **Training & Optimization**:
  - Standard Training
  - Training with **Gradient Accumulation**
- **Testing & Baselines**:
  - **Random Tour** Baseline
  - **Greedy Algorithm** Baseline
  - **Transformer Model Evaluation**
- **Performance Analysis**: Computes the **Optimality Gap** and generates boxplots for model evaluation.


## 📌 Model Architecture

The implemented transformer model consists of:

- **Transformer Encoder** (Processes input node coordinates)
- **Transformer Decoder** (Generates the optimal tour sequence)
- **Feedforward Neural Network** (Predicts node transitions)
- **Masking Mechanisms** (Handles constraints in tour generation)
- **Positional Encoding** (For the decoder, omitted in the encoder)



