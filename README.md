# Ridge Regression — Predicting Student Performance

[![Python](https://img.shields.io/badge/Python-3.x-blue)](https://www.python.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org/)


A minimal **Ridge Regression** pipeline (Jupyter Notebook) to predict student performance 

---


**Features (examples):**
- Hours Studied
- Previous Scores
- Sleep Hours
- Sample Question Papers Practiced
- Extracurricular Activities (categorical)

**Target:**
- Student Performance (numeric)

---

## 🛠 Methodology

1. **Load Data**: Using `pandas`.
2. **Handle Missing Values**: Impute numeric features with mean or median.
3. **Encode Categorical Features**: One-Hot or Label Encoding.
4. **Scale Numeric Features**: Standardization or normalization.
5. **Exploratory Data Analysis (EDA)**:
   - Correlations
   - Distributions
   - Custom visualizations
6. **Data Split**: 80% training / 20% testing (`random_state` set for reproducibility).
7. **Model**: `sklearn.linear_model.Ridge`.
8. **Evaluation Metric**: Mean Absolute Error (MAE) on the test set.

---

## 🚀 Usage

1. Clone the repository:
   ```bash
   git clone <repository-link>
