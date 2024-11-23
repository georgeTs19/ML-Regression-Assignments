# README

## Project Title: Optimization Methods - Assignment 5

### Overview
This repository contains the fifth assignment from the course **Machine Learning from a Regression Perspective**, part of the Master's program in **Data Analytics and Business Economics** at **Lund University**. The assignment focuses on applying optimization techniques in machine learning, emphasizing tuning and evaluation strategies to improve model performance.

---

### File Structure

- **`DABN13_Assignment5.ipynb`**  
  The Jupyter Notebook containing the complete workflow for implementing optimization techniques in machine learning models.

- **`dataset/`**
  - **`online_shoppers_intention.csv`**  
    A dataset containing user interaction data on e-commerce platforms, used to predict purchasing behavior.

---

### Dataset Information

#### `online_shoppers_intention.csv`
- **Observations**: Contains records of user sessions on e-commerce websites.
- **Features**:
  - Behavioral metrics: Number of pages visited, time spent on pages, bounce rates, and exit rates.
  - Contextual features: Month, operating system, browser, region, and traffic type.
  - Target variable: `Revenue` - Indicates whether a session resulted in a purchase.

---

### Assignment Objectives
This assignment focuses on:
1. Implementing optimization techniques to fine-tune machine learning models.
2. Exploring hyperparameter tuning methods (e.g., grid search, random search).
3. Comparing performance metrics for optimized and baseline models.
4. Understanding the trade-offs between computational cost and model performance in optimization.

Additional goals:
- Apply optimization techniques to classification models (e.g., logistic regression, decision trees).
- Evaluate and visualize the impact of tuning on key metrics (e.g., accuracy, precision, recall, F1-score).

---

### Instructions
1. **Setup**:
   - Clone this repository to your local machine:
     ```bash
     git clone https://github.com/georgeTs19/ML-Regression-Assignments.git
     ```
   - Navigate to the `Optimization-Methods` folder in the repository.

2. **Environment**:
   - Open the `DABN13_Assignment5.ipynb` file using Jupyter Notebook or a compatible environment.
   - Ensure the dataset (`online_shoppers_intention.csv`) is placed in the `dataset/` directory.

3. **Workflow**:
   - Load and preprocess the dataset.
   - Split the dataset into training and testing sets.
   - Apply optimization techniques to fine-tune machine learning models.
   - Evaluate and compare model performance before and after optimization.

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
   - Preprocessing and splitting the dataset.
   - Implementation of optimization methods.
   - Evaluation and visualization of optimized models.
2. Insights into the trade-offs of various optimization strategies.
3. Conclusions on the effectiveness of optimization techniques in machine learning.

---

### Acknowledgments
This assignment and dataset are part of the **DABN13** course, focusing on machine learning applications in business and economics. The course is a component of the Master's program at Lund University.

---
