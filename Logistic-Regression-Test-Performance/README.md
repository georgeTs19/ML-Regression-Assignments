# README

## Project Title: Machine Learning from a Regression Perspective - Assignment 2

### Overview
This repository contains the second assignment from the course **Machine Learning from a Regression Perspective**, part of the Master's program in **Data Analytics and Business Economics** at **Lund University, Sweden**. This assignment builds on foundational regression techniques and extends them to classification problems. The focus is on understanding the interplay between feature engineering, model selection, and classification performance metrics.

---

### File Structure

- **`DABN13_Assignment2.ipynb`**  
  The Jupyter Notebook contains the complete workflow, including data preprocessing, feature engineering, and classification model development and evaluation.

- **`dataset/`**
  - **`online_shoppers_intention.csv`**  
    A CSV file containing data on user interactions with e-commerce platforms, used to predict purchasing intent.
  - **`drug_train.RDS`** and **`drug_test.RDS`**  
    RDS files containing training and testing datasets for drug classification tasks.

---

### Dataset Information

#### Online Shoppers Intention Dataset
- **Observations**: 12,330 rows and 18 columns.
- **Features**:
  - **Behavioral Metrics**: BounceRates, ExitRates, PageValues, etc.
  - **Contextual Features**: Month, Operating Systems, Browser, Region, Traffic Type, Visitor Type, and Weekend indicator.
  - **Target Variable**: `Revenue` - Boolean indicating whether the session resulted in a transaction.
- **Source**: Part of the course material, showcasing regression-based classification techniques.

#### Drug Classification Dataset
- **Training and Testing Data**:
  - `drug_train.RDS`: Contains labeled data for training classification models.
  - `drug_test.RDS`: Contains data for testing model performance.
- **Details**: This dataset involves categorical and continuous predictors to classify drug responses. Specific feature details are provided in the notebook.

---

### Assignment Objectives
This assignment focuses on:
1. Applying feature engineering techniques to improve model performance.
2. Exploring relationships between predictors and the target variable in classification problems.
3. Evaluating classification models, including logistic regression and other advanced techniques.
4. Using model performance metrics (e.g., accuracy, precision, recall, F1-score) to compare and interpret results.
5. Generating actionable insights for business decision-making based on model outputs.

Additional goals:
- Perform exploratory data analysis (EDA) to uncover trends and inform feature selection.
- Implement cross-validation techniques to ensure robust model evaluation.
- Develop a systematic approach to preprocess and analyze datasets for classification tasks.

---

### Instructions
1. **Setup**:
   - Clone this repository to your local machine:
     ```bash
     git clone https://github.com/georgeTs19/ML-Regression-Assignments.git
     ```
   - Navigate to the `Logistic-Regression-Test-Performance` folder in the repository.

2. **Environment**:
   - Open the `DABN13_Assignment2.ipynb` file using Jupyter Notebook or any compatible environment.
   - Ensure the datasets (`online_shoppers_intention.csv`, `drug_train.RDS`, and `drug_test.RDS`) are placed in the `dataset/` directory.

3. **Workflow**:
   - Load, clean, and preprocess the datasets.
   - Perform EDA to explore variable distributions and relationships.
   - Fit and evaluate classification models, including logistic regression and others.
   - Document actionable insights based on classification results.

---

### Requirements
- **Python Environment**:
  - `pandas`
  - `numpy`
  - `statsmodels`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
  - `pyreadr` (for RDS file support)

- **RDS File Support**:
  Install `pyreadr` to process `.RDS` files:
  ```bash
  pip install pyreadr


---

### Key Deliverables
1. A comprehensive Jupyter Notebook showcasing:
   - Data preprocessing and feature engineering.
   - Exploratory Data Analysis (EDA).
   - Classification model development and evaluation.
   - Interpretation of model performance metrics.
2. Visualizations highlighting key findings and trends.
3. Written conclusions with actionable recommendations

---

### Acknowledgments
This assignment and datasets are part of the DABN13 course, focusing on machine learning applications in business and economics. The course is a component of the Master's program at Lund University.

---

