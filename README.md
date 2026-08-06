# unsupervised-learning-pca-tsne
Dimensionality reduction and unsupervised machine learning workflow using PCA and t-SNE to explore high-dimensional data, identify patterns, visualize sample relationships, and extract meaningful insights from the Auto dataset.

# PCA and t-SNE Analysis of the Auto MPG Dataset

## Overview

The objective was to apply dimensionality reduction techniques to explore high-dimensional data, identify underlying patterns, and visualize relationships between samples in the Auto MPG dataset.

Principal Component Analysis (PCA) and t-distributed Stochastic Neighbor Embedding (t-SNE) were implemented using Python and Scikit-learn to reduce data dimensionality while preserving meaningful structure for visualization and interpretation.

---

## Dataset

The project uses the **Auto MPG** dataset, which contains vehicle characteristics such as:

- MPG
- Cylinders
- Displacement
- Horsepower
- Weight
- Acceleration
- Model Year
- Origin

---

## Project Workflow

```text
Load Dataset
      ↓
Data Inspection
      ↓
Data Cleaning
      ↓
Exploratory Data Analysis (EDA)
      ↓
Feature Scaling (StandardScaler)
      ↓
Principal Component Analysis (PCA)
      ↓
Principal Component Interpretation
      ↓
t-SNE Visualization
      ↓
Pattern Identification
      ↓
Data Interpretation
```

---

## Analysis Performed

- Loaded and explored the Auto MPG dataset.
- Performed data cleaning and preprocessing.
- Standardized numerical features using StandardScaler.
- Applied Principal Component Analysis (PCA) to reduce dimensionality.
- Evaluated the explained variance captured by principal components.
- Visualized the dataset using PCA.
- Applied t-distributed Stochastic Neighbor Embedding (t-SNE) for nonlinear dimensionality reduction.
- Compared PCA and t-SNE visualizations to identify hidden patterns and sample relationships.
- Interpreted the resulting low-dimensional representations.

---

## Methods Used

- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Feature Scaling
- Principal Component Analysis (PCA)
- t-distributed Stochastic Neighbor Embedding (t-SNE)
- Data Visualization

---

## Software & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## Skills Demonstrated

- Machine Learning
- Unsupervised Learning
- Dimensionality Reduction
- Feature Engineering
- Data Visualization
- Exploratory Data Analysis
- Statistical Analysis
- Scientific Computing

---

## Repository Structure

```text
pca-tsne-auto-mpg-analysis/
│
├── README.md
├── auto_mpg_pca_tsne.ipynb
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## Notes

This repository demonstrates the application of unsupervised machine learning techniques for dimensionality reduction and visualization. The project highlights the complete analytical workflow, from data preprocessing to interpretation of PCA and t-SNE results.

---


## Author

**Vijay Jidigam, Ph.D.**

https://www.linkedin.com/in/vijay-jidigam-4921b48/
