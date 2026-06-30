# AI Course Labs

Repository with projects and assignments from my **Artificial Intelligence** course, covering fundamental AI techniques from classical machine learning to evolutionary computation and fuzzy systems.

---

## Overview

This repository contains **10 lab assignments** that explore core concepts in Artificial Intelligence and Machine Learning, progressing from foundational data manipulation through classical ML, deep learning, evolutionary algorithms, and fuzzy logic systems.

| # | Topic |
|---|-------|
| 1 | NumPy & Matplotlib |
| 2 | Data Preprocessing |
| 3 | Decision Trees |
| 4 | PyTorch & Activation Functions |
| 5 | MLP for Binary Addition |
| 6 | Classification Models |
| 7 | Computer Vision & CNNs |
| 8 | Evolutionary Computation |
| 9 | Aircraft Design Optimization |
| 10 | Fuzzy Logic Systems |

---

## Concepts Covered

### Data Preprocessing & Visualization
Feature engineering fundamentals for ML pipelines. Covers standardization (removing mean, scaling to unit variance), Min-Max scaling, MaxAbs scaling, L2 normalization of samples, and encoding categorical features. Uses **NumPy** for array operations (creation, indexing, slicing, broadcasting, random sampling) and **Matplotlib** for data visualization.

### Classical Machine Learning
Supervised learning with **Decision Trees** on the Iris dataset. Includes data cleaning, label encoding, train/test splitting, entropy-based tree construction, hyperparameter tuning via `GridSearchCV`, and tree visualization.

### Neural Networks & Deep Learning
Progressive exploration of deep learning with **PyTorch**:
- **Autograd** : automatic differentiation, gradient computation for activation functions (Sigmoid, ReLU, Linear)
- **Multilayer Perceptrons** : feedforward networks for binary addition (XOR-like problem), comparing ReLU, Tanh, and Sigmoid activations
- **Classification** : linear vs. non-linear classifiers, multiclass classification pipeline
- **Computer Vision** : image tensors, convolution kernels (blur, sharpen, edge detection), pooling, training CNNs vs. linear models

### Evolutionary Computation
Bio-inspired optimization techniques:
- **Genetic Algorithms** : selection, crossover, mutation with binary representation
- **Multi-Objective Optimization** : NSGA-II with non-dominated sorting, crowding distance, Pareto front analysis
- **Real-World Application** : aircraft design optimization with 6 continuous variables (wing span, area, sweep angle, thickness-to-chord ratio, fuselage length/diameter), constraint handling via penalty functions, SBX crossover, polynomial mutation

### Fuzzy Logic & Rule-Based Systems
Reasoning under uncertainty using **Mamdani fuzzy inference**:
- **Membership functions** : triangular and trapezoidal
- **Fuzzification** : mapping crisp inputs to fuzzy membership degrees
- **Linguistic rules** : IF–THEN rules with `min` for implication and `max` for accumulation
- **Defuzzification** : centroid method for crisp output
- **Case study** : autonomous delivery robot speed recommendation based on visibility, obstacle distance, and battery level
