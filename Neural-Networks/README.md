# README

## Project Title: Neural Networks - Assignment 6

### Overview
This repository contains the sixth assignment from the course **Machine Learning from a Regression Perspective**, part of the Master's program in **Data Analytics and Business Economics** at **Lund University**. The assignment focuses on implementing neural networks to model complex relationships in data, emphasizing applications in regression and classification tasks.

---

### File Structure

- **`DABN13_Assignment6.ipynb`**  
  The Jupyter Notebook containing the complete workflow for building, training, and evaluating neural networks.

- **`dataset/`**
  - **`LightBeer2.csv`**  
    A dataset containing data on light beer characteristics, used to model relationships using neural networks.

---

### Dataset Information

#### `LightBeer2.csv`
- **Observations**: Contains records of various characteristics related to light beers.
- **Features**:
  - Potential predictors such as chemical composition, sensory ratings, and production details.
  - The target variable may represent quality scores, consumer ratings, or other performance metrics.

---

### Assignment Objectives
This assignment focuses on:
1. Designing, training, and evaluating neural networks for regression or classification tasks.
2. Exploring the impact of hyperparameter tuning (e.g., learning rate, number of layers) on neural network performance.
3. Comparing neural network performance with traditional regression-based methods.
4. Visualizing model predictions and performance metrics to interpret results effectively.

Additional goals:
- Handle overfitting through techniques such as dropout and regularization.
- Use advanced optimizers (e.g., Adam, SGD) to improve training efficiency.

---

### Instructions
1. **Setup**:
   - Clone this repository to your local machine:
     ```bash
     git clone https://github.com/georgeTs19/ML-Regression-Assignments.git
     ```
   - Navigate to the `Neural-Networks` folder in the repository.

2. **Environment**:
   - Open the `DABN13_Assignment6.ipynb` file using Jupyter Notebook or a compatible environment.
   - Ensure the dataset (`LightBeer2.csv`) is placed in the `dataset/` directory.

3. **Workflow**:
   - Load and preprocess the dataset.
   - Design and implement a neural network architecture.
   - Train and evaluate the neural network on the dataset.
   - Compare results with baseline models and document key insights.

---

### Requirements
- **Python Environment**:
  - `pandas`
  - `numpy`
  - `tensorflow` or `pytorch`
  - `matplotlib`

---

### Key Deliverables
1. A Jupyter Notebook demonstrating:
   - Preprocessing and exploratory analysis of the dataset.
   - Implementation of a neural network model for prediction tasks.
   - Evaluation of model performance using metrics like accuracy, RMSE, or \(R^2\).
2. Visualizations showcasing training progress, model performance, and key insights.
3. Conclusions on the effectiveness of neural networks in solving the problem.

---

### Acknowledgments
This assignment and dataset are part of the **DABN13** course, focusing on machine learning applications in business and economics. The course is a component of the Master's program at Lund University.

---
