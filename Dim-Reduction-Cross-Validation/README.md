# README

## Project Title: Dimensionality Reduction and Cross-Validation - Assignment 3

### Overview
This repository contains the third assignment from the course **Machine Learning from a Regression Perspective**, part of the Master's program in **Data Analytics and Business Economics** at **Lund University, Sweden**. The assignment focuses on applying dimensionality reduction techniques, such as Principal Component Analysis (PCA), alongside cross-validation to build robust regression models for financial datasets.

---

### File Structure

- **`DABN13_Assignment3.ipynb`**  
  The Jupyter Notebook containing the complete workflow for dimensionality reduction, regression modeling, and cross-validation.

- **`dataset/`**
  - **`sorted_portfolios100.csv`**  
    Contains numerical features of portfolios, potentially representing returns or characteristics.
  - **`twelve_month_returns.csv`**  
    Contains 12-month return values corresponding to portfolios in the first dataset.

---

### Dataset Information

#### `sorted_portfolios100.csv`
- **Observations**: 600 rows and 101 columns.
- **Features**:
  - **Columns**: A unique identifier (`Unnamed: 0`) and 100 numerical features (`V2` to `V101`).
  - Likely represents portfolio characteristics or asset returns over time.

#### `twelve_month_returns.csv`
- **Observations**: 600 rows and 2 columns.
- **Features**:
  - `Unnamed: 0`: Unique identifier.
  - `x`: Represents 12-month returns for corresponding portfolios or assets.

---

### Assignment Objectives
This assignment focuses on:
1. Applying dimensionality reduction (e.g., PCA) to reduce the number of predictors while preserving essential variance.
2. Implementing regression models in a pipeline incorporating standardization and PCA.
3. Evaluating model performance using cross-validation techniques.
4. Using predictions to understand relationships between portfolio features and 12-month returns.

Additional goals:
- Compare models with and without dimensionality reduction to evaluate PCA's impact.
- Develop robust workflows combining feature engineering, model building, and validation.

---

### Instructions
1. **Setup**:
   - Clone this repository to your local machine:
     ```bash
     git clone https://github.com/georgeTs19/ML-Regression-Assignments.git
     ```
   - Navigate to the `Dim-Reduction-Cross-Validation` folder in the repository.

2. **Environment**:
   - Open the `DABN13_Assignment3.ipynb` file using Jupyter Notebook or a compatible environment.
   - Ensure the datasets (`sorted_portfolios100.csv` and `twelve_month_returns.csv`) are placed in the `dataset/` directory.

3. **Workflow**:
   - Load and preprocess the datasets.
   - Apply PCA to reduce feature dimensions.
   - Build regression models with and without PCA for comparison.
   - Use cross-validation to assess model performance and robustness.

---

### Requirements
- **Python Environment**:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`

---

### Key Deliverables
1. A Jupyter Notebook illustrating:
   - Dimensionality reduction using PCA.
   - Regression model development and evaluation.
   - Cross-validation workflows and model comparisons.
2. Visualizations highlighting the effect of PCA and model performance.
3. Written conclusions with actionable recommendations for financial portfolio management.

---

### Acknowledgments
This assignment and datasets are part of the **DABN13** course, focusing on machine learning applications in business and economics. The course is a component of the Master's program at Lund University.

---

