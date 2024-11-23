# README

## Project Title: Machine Learning from a Regression Perspective - Assignment 1

### Overview
This repository contains the first assignment from the course **Machine Learning from a Regression Perspective**, part of the Master's program in **Data Analytics and Business Economics** at **Lund University, Sweden**. The assignment emphasizes hands-on application of regression-based machine learning techniques, highlighting their utility in solving complex problems within business and economics.

---

### File Structure

- **`DABN13_Assignment1.ipynb`**  
  The Jupyter Notebook contains the complete workflow, including data preprocessing, modeling, and result interpretation. The focus is on building a robust regression model to address specific questions tied to the dataset.

- **`dataset/`**
  - **`Guns.dta`**  
    A Stata dataset used in the assignment. It includes socioeconomic and policy-related variables that serve as predictors in regression analyses.

---

### Dataset Information

- **Dataset Name:** Guns.dta  
- **Format:** Stata (.dta)  
- **Description:**  
  This dataset examines the relationships between gun-related laws, demographic characteristics, and socioeconomic factors. It is used to develop regression models and uncover trends or patterns.  
- **Variables:**  
  - `year`: Year of observation.
  - `vio`: Violent crime rate.
  - `mur`: Murder rate.
  - `rob`: Robbery rate.
  - `incarc_rate`: Incarceration rate.
  - `pb1064`, `pw1064`, `pm1029`: Proportions of demographic groups by age, gender, and race.
  - `pop`: State population.
  - `avginc`: Average income.
  - `density`: Population density.
  - `stateid`: State identifier.
  - `shall`: Binary indicator for "shall-issue" gun law (1 = Yes, 0 = No).  

- **Source:**  
  Provided as part of the course materials, this dataset demonstrates the practical application of regression-based techniques to real-world data.

---

### Assignment Objectives
This assignment focuses on:
1. Understanding and preparing real-world datasets for regression analysis.
2. Evaluating the predictive power of multiple regression models and diagnosing common issues (e.g., outliers, multicollinearity).
3. Applying shrinkage methods such as ridge and lasso regression for improved generalization and feature selection.
4. Leveraging regression techniques to derive actionable insights from data, particularly in policy analysis or decision-making contexts.
5. Visualizing model outcomes and communicating findings effectively.

Additional goals:
- Explore relationships between variables through exploratory data analysis (EDA).
- Compare and interpret results from multiple regression techniques, identifying strengths and weaknesses of each.
- Deliver actionable insights and recommendations based on model findings, particularly in the context of gun policy analysis.

---

### Instructions
1. **Setup**:
   - Clone this repository to your local machine:
     ```bash
     git clone https://github.com/georgeTs19/ML-Regression-Assignments.git
     ```
   - Navigate to the `Linear-Regression` folder in the repository.

2. **Environment**:
   - Open the `DABN13_Assignment1.ipynb` file using Jupyter Notebook or any compatible environment.
   - Ensure the dataset (`Guns.dta`) is placed in the `dataset/` directory for seamless data loading.
   - Install the required Python libraries (see the Requirements section).

3. **Workflow**:
   - Load, clean, and preprocess the dataset.
   - Explore variable relationships through descriptive statistics and visualizations.
   - Fit and evaluate multiple regression models, including OLS, Ridge, and Lasso.
   - Compare models and document actionable insights for policy recommendations.

---

### Requirements
- **Python Environment**:
  - `pandas`
  - `numpy`
  - `statsmodels`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn` (for ridge and lasso regression)

- **Stata File Support**:
  Ensure your environment can process `.dta` files using libraries like `pandas`.

---

### Key Deliverables
1. A comprehensive Jupyter Notebook showcasing:
   - Data preparation and preprocessing.
   - Exploratory Data Analysis (EDA).
   - Regression analysis and model comparisons.
   - Interpretations and actionable insights.
2. Visualizations supporting findings and highlighting key trends.
3. Written conclusions derived from regression outputs.

---

### Acknowledgments
This assignment and dataset are part of the **DABN13** course, focusing on the application of machine learning techniques in business and economics. The course is a component of the Master's program at Lund University.

---


