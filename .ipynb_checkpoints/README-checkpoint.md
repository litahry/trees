# Decision Tree & Pruning Experiments (Scaffolded ML Project)

This project explores **decision stumps, unpruned trees, and pruned decision trees** applied across multiple datasets.  
It was originally implemented as a **single, exploratory Jupyter notebook**.  
Since then, I have **refactored and scaffolded** the project into a modular, professional structure aligned with industry best practices.

---

## Project Overview

**Objective:**  
Implement and compare:
1. Decision Stump  
2. Unpruned Decision Tree  
3. Pruned Decision Tree (pre- and post-pruning strategies)

For each dataset:
- Handle missing values appropriately.  
- Perform cross-validation and hyperparameter tuning.  
- Compare methods statistically (Wilcoxon signed-rank test with Holm correction).  
- Discuss why some models perform worse and interpret findings.

---

## Evolution of the Project

**Before:**  
- Everything lived in one large notebook (`.ipynb`).  
- Preprocessing, modeling, and evaluation were mixed together.  
- Difficult to test, reproduce, or share on GitHub.

**Now:**  
- The project is fully scaffolded following **Cookiecutter Data Science** and **PyPA Packaging** guidelines
- 
- **Key improvements:**
- Reusable, importable Python package (`trees_experiments`).
- Consistent preprocessing via `ColumnTransformer`.
- Version-controlled notebooks with clean diffs.
- Git best practices (feature branches, small commits, meaningful messages).
- Proper citations and documentation of methods.

---

## Learning & Rationale

I refactored this project to learn:
- **Software architecture for data science projects.**
- **Clean code principles** (single responsibility, modular design, descriptive naming).
- **Version control discipline** (GitHub Flow, commits, and branching).
- **Reproducibility** using environment management (`conda`, `pip install -e .`).

This process improved not just performance tracking, but **clarity, collaboration potential, and reusability**.

---

## Tools & Libraries

- Python 3.10 (Anaconda)
- pandas, NumPy, scikit-learn, SciPy, statsmodels
- JupyterLab
- Git + GitHub for version control

---