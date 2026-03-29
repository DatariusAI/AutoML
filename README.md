<div align="center">

# :gear: AutoML

### Automated machine learning: model selection, hyperparameter optimization, feature engineering, and neural architecture search

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Auto-sklearn](https://img.shields.io/badge/Auto--sklearn-F7931E?style=for-the-badge)](https://automl.github.io/auto-sklearn/)
[![Optuna](https://img.shields.io/badge/Optuna-2496ED?style=for-the-badge)](https://optuna.org/)
[![FLAML](https://img.shields.io/badge/FLAML-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)](https://microsoft.github.io/FLAML/)

</div>

---

## Overview

A comprehensive portfolio of Automated Machine Learning (AutoML) projects demonstrating how to systematically automate the end-to-end ML pipeline. Covers automated model selection, hyperparameter optimization, feature engineering, and neural architecture search using state-of-the-art frameworks and custom implementations.

## Topics Covered

| # | Topic | Description | Status |
|---|-------|-------------|--------|
| 1 | **Hyperparameter Optimization** | Bayesian optimization, TPE, random search, and grid search with Optuna | :construction: Planned |
| 2 | **Automated Model Selection** | Comparing and selecting the best model from a portfolio of algorithms | :construction: Planned |
| 3 | **Auto-sklearn** | End-to-end AutoML with meta-learning and ensemble construction | :construction: Planned |
| 4 | **FLAML** | Fast, lightweight AutoML with cost-effective hyperparameter tuning | :construction: Planned |
| 5 | **Feature Engineering** | Automated feature generation, selection, and transformation | :construction: Planned |
| 6 | **Neural Architecture Search** | Automated design of neural network architectures (NAS) | :construction: Planned |
| 7 | **AutoML Benchmarking** | Comparing AutoML frameworks on standard datasets | :construction: Planned |
| 8 | **Custom AutoML Pipeline** | Building a custom AutoML system from scratch | :construction: Planned |
| 9 | **Multi-Objective Optimization** | Pareto-optimal solutions balancing accuracy, latency, and model size | :construction: Planned |
| 10 | **AutoML in Production** | Deploying AutoML pipelines with automated retraining triggers | :construction: Planned |

## Tech Stack

| Category | Tools |
|----------|-------|
| **Languages** | Python |
| **AutoML Frameworks** | Auto-sklearn, FLAML, AutoGluon, H2O AutoML |
| **Optimization** | Optuna, Hyperopt, Ray Tune, BOHB |
| **ML Libraries** | scikit-learn, XGBoost, LightGBM, CatBoost |
| **NAS** | NNI, KerasTuner, AutoKeras |
| **Feature Engineering** | Featuretools, tsfresh, OpenFE |
| **Experiment Tracking** | MLflow, Weights & Biases |

## Project Structure

```
AutoML/
|-- hyperparameter_optimization/   # HPO experiments with Optuna & others
|-- model_selection/               # Automated model selection pipelines
|-- auto_sklearn/                  # Auto-sklearn projects
|-- flaml/                         # FLAML experiments
|-- feature_engineering/           # Automated feature engineering
|-- nas/                           # Neural architecture search
|-- benchmarks/                    # Framework comparison benchmarks
|-- custom_pipeline/               # Custom AutoML implementation
|-- notebooks/                     # Exploratory notebooks
`-- README.md
```

## Getting Started

```bash
# Clone the repository
git clone https://github.com/DatariusAI/AutoML.git
cd AutoML

# Create virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt
```

## Roadmap

- [ ] Optuna hyperparameter optimization cookbook
- [ ] Auto-sklearn vs. FLAML vs. AutoGluon benchmark
- [ ] Automated feature engineering pipeline with Featuretools
- [ ] Neural Architecture Search with NNI
- [ ] Custom AutoML framework from scratch
- [ ] Multi-objective optimization for edge deployment
- [ ] Production AutoML pipeline with drift detection

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

<div align="center">

**Part of the [DatariusAI](https://github.com/DatariusAI) portfolio**

</div>
