# README

## Project Title: Regularization Techniques - Assignment 4

### Overview
This repository contains the fourth assignment from the course **Machine Learning from a Regression Perspective**, part of the Master's program in **Data Analytics and Business Economics** at **Lund University**. The assignment focuses on applying regularization techniques, such as Ridge and Lasso regression, to handle multicollinearity and improve model performance.

---

### File Structure

- **`DABN13_Assignment4.ipynb`**  
  The Jupyter Notebook containing the complete workflow for applying regularization techniques in regression models.

- **`dataset/`**
  - **`Airfares.csv.gz`**  
    A compressed dataset containing information about airfare prices and related predictors, used for regression analysis.

---

### Dataset Information

#### `Airfares.csv.gz`
- **Observations**: Contains records of airfare prices and other relevant features.
- **Features**:
  - Potential predictors such as distance, demand, airline features, and airport characteristics.
  - The target variable represents airfare prices.

---

### Assignment Objectives
This assignment focuses on:
1. Understanding the impact of multicollinearity on regression models.
2. Applying Ridge and Lasso regression to address multicollinearity and enhance predictive accuracy.
3. Comparing the performance of regularized models with standard linear regression.
4. Tuning hyperparameters (e.g., regularization strength) to optimize model performance.

Additional goals:
- Visualize feature coefficients for different levels of regularization.
- Interpret the effects of regularization on model complexity and accuracy.

---

### Instructions
1. **Setup**:
   - Clone this repository to your local machine:
     ```bash
     git clone https://github.com/georgeTs19/ML-Regression-Assignments.git
     ```
   - Navigate to the `Regularization` folder in the repository.

2. **Environment**:
   - Open the `DABN13_Assignment4.ipynb` file using Jupyter Notebook or a compatible environment.
   - Ensure the dataset (`Airfares.csv.gz`) is placed in the `dataset/` directory.

3. **Workflow**:
   - Load and preprocess the dataset.
   - Fit Ridge and Lasso regression models to predict airfare prices.
   - Evaluate and compare model performance using metrics such as RMSE or \(R^2\).
   - Visualize the impact of regularization on feature coefficients.

---

### Requirements
- **Python Environment**:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`

---

### Key Deliverables
1. A Jupyter Notebook demonstrating:
   - Data preprocessing and exploratory analysis.
   - Ridge and Lasso regression model implementation.
   - Hyperparameter tuning for optimal regularization.
2. Visualizations showcasing the effects of regularization.
3. Written conclusions on the benefits and trade-offs of regularization in regression.

---

### Acknowledgments
This assignment and dataset are part of the **DABN13** course, focusing on machine learning applications in business and economics. The course is a component of the Master's program at Lund University.

---
