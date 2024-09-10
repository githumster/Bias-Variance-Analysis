# Bootstrap Bias and Variance Evaluation

This project aims to evaluate the bias and variance of machine learning algorithms using bootstrap techniques. The evaluation is performed on the Boston housing dataset, which contains various features about housing in Boston and is commonly used for regression tasks.

## Dataset

The model is trained and evaluated using the Boston housing dataset, which provides information about housing prices in Boston. You can access the dataset via the `sklearn.datasets` module.

## Project Overview

The project includes the following tasks:

1. **Bias and Variance Calculation Using Bootstrap**  
   Implemented an algorithm to estimate the bias and variance of regression models using bootstrap sampling. The process involves:
   - Generating bootstrap samples.
   - Training models on these samples.
   - Evaluating predictions on out-of-bag samples.
   - Calculating bias, variance, and error based on these predictions.

2. **Model Evaluation**  
   Evaluated the bias, variance, and error for three algorithms with default hyperparameters: Linear Regression, Decision Tree, and Random Forest.

3. **Analysis of Results**  
   Analyzed the results obtained from the models to check if they align with theoretical expectations. Provided comments on the observed bias and variance for each algorithm.

4. **Bagging Models and Variance Reduction**  
   Implemented bagging over the three models (Linear Regression, Decision Tree, Random Forest) and analyzed how bagging affects variance. Compared theoretical expectations with experimental results.

5. **Visualization of Model Predictions**  
   Developed a function to visualize predictions from different models. The function generates scatter plots showing predictions for randomly selected test objects from the dataset. Each plot visualizes the spread of predictions and compares them to the true values.

6. **Hyperparameter Impact Analysis**  
   Plotted how changing hyperparameters (e.g., max_depth for Decision Trees, n_estimators for Random Forest and Gradient Boosting) affects bias and variance.

## Code Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/githumster/bootstrap-bias-variance.git
