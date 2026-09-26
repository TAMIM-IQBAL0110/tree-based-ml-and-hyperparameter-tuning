# Tree-Based Machine Learning Algorithms & Hyperparameter Tuning

This repository contains my implementations of tree-based machine learning algorithms and my practice with hyperparameter tuning using **scikit-learn**.

Over the last few days, I learned how tree-based algorithms evolved from a single Decision Tree to modern boosting algorithms like XGBoost, LightGBM, and CatBoost. Along with implementing each algorithm, I also tuned them using three different hyperparameter optimization techniques.

## What I implemented

- Decision Tree
- Random Forest
- Extra Trees
- AdaBoost
- Gradient Boosting
- XGBoost
- LightGBM
- CatBoost

Each algorithm has its own Jupyter Notebook with implementation, training, evaluation, and tuning.

## Hyperparameter Tuning

For every tree-based model, I experimented with three tuning approaches:

- **Grid Search** – tries every parameter combination.
- **Random Search** – samples random combinations to reduce search time.
- **Bayesian Optimization** – intelligently searches promising parameter values.

All implementations are done using **scikit-learn**, while Bayesian Optimization is implemented with **Optuna**.

## Repository Structure

```text
├── DecisionTree.ipynb
├── RandomForest.ipynb
├── XtraTree.ipynb
├── AdaBoost.ipynb
├── GradientBoosting.ipynb
├── XGBoost.ipynb
├── LightGBM.ipynb
├── CatBoost.ipynb
└── catboost_info/
