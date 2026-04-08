<div align="center">

<img src="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/other/official-artwork/150.png" width="120"/>

# ML Algorithms & PokéLab

**A hands-on journey through Machine Learning — from clustering to optimization — with Pokémon data as the playground.**

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?style=flat-square&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Optuna](https://img.shields.io/badge/Optuna-HPO-3499E0?style=flat-square)](https://optuna.org/)
[![Docker](https://img.shields.io/badge/Docker-Ready-2496ED?style=flat-square&logo=docker&logoColor=white)](https://www.docker.com/)

</div>

---

## About this repo

This repository collects four machine learning assignments, each tackling a different area of the ML landscape. Notebooks are self-contained, well-documented, and designed to be run top-to-bottom.

---

## Modules

| # | Topic | Dataset | Goal |
|---|-------|---------|------|
| [01](01-clustering/) | **Clustering** | Ice-cream customer data (*La Vía Láctea*) | Segment customers for a marketing campaign using unsupervised learning |
| [02](02-clasification/) | **Classification** | Pokédex | Binary classification — predict whether a Pokémon is Legendary |
| [03](03-regression/) | **Regression** | Pokédex | Predict a Pokémon's Attack stat using regression models |
| [04](04-optimization/) | **Hyperparameter Optimization** | Pokédex | Push classification performance further using systematic HPO |

---

## Techniques covered

**Unsupervised**
- K-Means, Hierarchical Clustering
- EDA with Shapiro-Wilk, ANOVA, pairplots

**Classification**
- Logistic Regression, Decision Trees, Random Forest, SVM, KNN
- Handling class imbalance (SMOTE / imbalanced-learn)

**Regression**
- Linear Regression, Ridge, Lasso, Polynomial features
- Cross-validation, RMSE / R² evaluation

**Optimization**
- Optuna — Bayesian hyperparameter search
- Grid Search, Random Search
- Learning curves & model selection

---

## Stack

```
pandas · numpy · matplotlib · seaborn
scikit-learn · imbalanced-learn · optuna
```

---

## Quickstart

### Option A — Docker (recommended)

```bash
docker build -t ml-algorithms .
docker run -p 8888:8888 ml-algorithms
```

Then open the URL printed in the terminal.

### Option B — Local

```bash
pip install -r requirements.txt
jupyter notebook
```

---

## Structure

```
ml-algorithms/
├── 01-clustering/
│   ├── clustering.ipynb
│   └── customer_data.csv
├── 02-clasification/
│   └── clasification.ipynb
├── 03-regression/
│   └── MD005_E3_Regression_Paulina-Peralta.ipynb
├── 04-optimization/
│   └── MD005_E4_Optimization_Paulina-Peralta.ipynb
├── requirements.txt
├── Dockerfile
└── README.md
```

---

<div align="center">

*Made by **Paulina Peralta** · 2026*

<img src="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/25.png" width="40"/>
<img src="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/6.png" width="40"/>
<img src="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/131.png" width="40"/>
<img src="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/143.png" width="40"/>

</div>
