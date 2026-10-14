# Machine Learning: Academic Coursework & Laboratory Notebooks

[![BSU FAMCS](https://img.shields.io/badge/BSU%20FAMCS-Curriculum%20Archive-blue.svg)](https://fpmi.bsu.by/)
[![Python 3.9+](https://img.shields.io/badge/Python-3.9%2B-3776AB.svg)](https://python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626.svg)](https://jupyter.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.0%2B-F7931E.svg)](https://scikit-learn.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

An academic repository comprising practical laboratory notebooks and algorithm implementations from the Machine Learning curriculum at Belarusian State University, Faculty of Applied Mathematics and Computer Science. Maintained as an open educational archive.

---

## Table of Contents
1. [Curriculum Overview](#curriculum-overview)
2. [Environment Setup](#environment-setup)
3. [Directory Structure](#directory-structure)
4. [License](#license)

---

## Curriculum Overview

| Module | Core Topic | Algorithmic Implementation |
| :--- | :--- | :--- |
| **`hw01_setup_tools`** | Environment & Vectorization | Vector operations with NumPy and array manipulation |
| **`hw02_dataset_analys`** | Exploratory Data Analysis | Feature normalization, variance analysis, correlation matrices |
| **`hw03_KNN`** | Metric Classification | $k$-Nearest Neighbors, Euclidean and Manhattan distance metrics, hyperparameter optimization |
| **`hw04_linear_regression`** | Linear Regression | Closed-form normal equations, batch gradient descent, Ridge and Lasso regularization |
| **`hw05_logreg`** | Logistic Classification | Binary cross-entropy optimization, sigmoid activation, ROC-AUC evaluation |
| **`hw06_naive_bayes`** | Probabilistic Modeling | Gaussian and Multinomial Naive Bayes, text tokenization, TF-IDF scoring |
| **`hw07_decision_tree`** | Tree Classifiers | Recursive splitting, Gini impurity, information gain, tree pruning |
| **`hw08_SVM`** | Support Vector Machines | Dual formulation, soft-margin optimization, radial basis function kernels |
| **`boosting.ipynb`** | Ensemble Methods | Sequential gradient boosting, AdaBoost, decision stumps, residual convergence |

---

## Environment Setup

### Prerequisites
* Python 3.9 or higher

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/botmaksim/ml-course-homeworks.git
   cd ml-course-homeworks
   ```

2. **Initialize Isolated Environment**
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install --upgrade pip
   ```

3. **Install Core Dependencies**
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn jupyter
   ```

4. **Launch Jupyter Server**
   ```bash
   jupyter notebook
   ```

---

## Directory Structure

```text
ml-course-homeworks/
├── hw01_setup_tools/       # Setup verification and vectorization benchmarks
├── hw02_dataset_analys/    # Exploratory data analysis routines
├── hw03_KNN/               # Metric k-NN classifier implementation
├── hw04_linear_regression/ # Linear models and regularized gradient descent
├── hw05_logreg/            # Logistic classification and cross-entropy
├── hw06_naive_bayes/       # Text classification and Naive Bayes
├── hw07_decision_tree/     # Decision tree induction and impurity metrics
├── hw08_SVM/               # Maximum-margin hyperplane optimization
├── boosting.ipynb          # Gradient boosting and ensemble analysis
└── README.md
```

---

## License

This repository is distributed under the [MIT License](LICENSE).
