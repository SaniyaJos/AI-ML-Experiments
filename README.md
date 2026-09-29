# AI & ML Lab

This repository contains the implementations and experiments completed as part of the **Artificial Intelligence and Machine Learning Lab**.

The work covers **data preprocessing, search algorithms, decision tree learning, regression, and other machine learning models** using Python.



## Experiments

### 1. Data Preprocessing

**Notebook:** `AI_ML_Lab_Exercise_1.ipynb`

This experiment focuses on preprocessing and preparing a student performance dataset for machine learning.

#### Tasks Performed

- Data Loading
- Missing Value Handling
- Duplicate Removal
- Outlier Detection
- Label Encoding
- One-Hot Encoding
- Feature Scaling
- Correlation Analysis
- Feature Engineering
- Train-Test Split
- Dataset Export

#### Dataset

**Student Performance Dataset (Kaggle)**

#### Output

The cleaned dataset saved as:

`cleaned_student_performance.csv`

---

### 2. Search Algorithms

This section contains implementations of different search strategies used in Artificial Intelligence.

#### A* Algorithm

**Notebook:** `A_algorithm.ipynb`

Implementation of the **A\*** search algorithm.

The evaluation function used by A* is:

\[
f(n) = g(n) + h(n)
\]

where:

- `g(n)` is the cost from the start node to node `n`
- `h(n)` is the heuristic estimate from node `n` to the goal

---

#### Greedy Best-First Search

**Notebook:** `Greedy_Best_First_Search.ipynb`

Implementation of the **Greedy Best-First Search** algorithm using heuristic-based node selection.

---

#### Uniform Cost Search

**Notebook:** `UCS_algorithm.ipynb`

Implementation of the **Uniform Cost Search (UCS)** algorithm, which selects nodes based on their path cost from the starting node.

---

#### Breadth-First Search and Depth-First Search

**Notebook:** `bfs,dfs.ipynb`

Implementation of two fundamental graph traversal/search algorithms:

- Breadth-First Search (BFS)
- Depth-First Search (DFS)

---

### 3. Decision Tree Learning

#### ID3 Algorithm

**Notebook:** `ID3_Algorithm.ipynb`

Implementation of the **ID3 decision tree algorithm**.

The experiment focuses on constructing a decision tree using the ID3 approach.

---

### 4. Regression

#### Linear Regression

**Notebook:** `Linear_Regression.ipynb`

Implementation of **Linear Regression** using the provided regression dataset.

**Dataset:**

`used_car_regression_lab_dataset.xlsx`

---

#### Regression Model Comparison

**Notebook:** `Random_forest,Decision_tree,SVM_Regression.ipynb`

This notebook contains regression-related implementations involving:

- Random Forest
- Decision Tree
- Support Vector Machine (SVM) Regression

---

## 📂 Datasets

The repository contains the datasets used in the experiments.

| Dataset | Purpose |
|---|---|
| `cleaned_student_performance.csv` | Cleaned output from the data preprocessing experiment |
| `student_performance_updated_1000-selected-...` | Student performance dataset |
| `used_car_regression_lab_dataset.xlsx` | Dataset used for regression experiments |
| `heart.csv` | Dataset taken for machine learning experiments |

---

## 🛠️ Tools & Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📁 Repository Structure

```text
AI-ML-Lab/
│
├── AI_ML_Lab_Exercise_1.ipynb
│
├── Search Algorithms/
│   ├── A_algorithm.ipynb
│   ├── Greedy_Best_First_Search.ipynb
│   ├── UCS_algorithm.ipynb
│   └── bfs,dfs.ipynb
│
├── ID3_Algorithm.ipynb
│
├── Linear_Regression.ipynb
├── Random_forest,Decision_tree,SVM_Regression.ipynb
│
├── cleaned_student_performance.csv
├── student_performance_updated_1000-selected-...
├── used_car_regression_lab_dataset.xlsx
├── heart.csv
│
└── README.md
