# MACHINE-LEARNING
3.1 Simple Linear Regression
This file focuses on simple linear regression using R. Key steps include:

Exploratory Data Analysis: Cleaning data and checking variable relationships.
Model Estimation: Fitting a simple linear regression model to analyze the relationship between one dependent variable and one independent variable.
Model Interpretation: Detailed evaluation of coefficients, p-values, R², and residual analysis.
Model Validation: Diagnosis of model assumptions using diagnostic plots (Residuals, QQ, and Leverage).
3.2 Multiple Linear Regression
This file explores multiple linear regression to model the relationship between one dependent variable and several independent variables. Key steps include:

Data Preprocessing: Handling missing values and exploring variable relationships.
Model Selection: Using stepwise regression techniques (backward and forward selection) to identify the optimal model based on AIC.
Model Interpretation: Analyzing the significance of coefficients, R², and residuals.
Model Validation: Performing diagnostics to validate assumptions of linearity, normality, homoscedasticity, and multicollinearity.
3.3 Non-Linear Regression and Model Comparison
This file deals with non-linear regression models and their comparison. The key sections include:

Polynomial Regression: Estimation of models of different polynomial degrees (linear, quadratic, cubic).
Step Functions: Splitting the data using cut-off points (with and without equidistribution) to fit stepwise models.
Splines Regression: Estimating polynomial splines using knots at specific intervals (manual or interquartile-based).
Model Comparison: Comparing models using goodness-of-fit metrics like R², AIC, and BIC, with graphical validation to select the best model.
4.1 Introduction to Supervised Classification Models
This file introduces supervised classification models for binary response variables using R. Key steps include:

Data Preparation: Ensuring the response variable is a factor with two levels and splitting the data into training and test sets.
Model Training: Applying algorithms like logistic regression, decision trees, or k-Nearest Neighbors (kNN) using the caret package.
Model Evaluation: Using accuracy, confusion matrices, and ROC-AUC to assess model performance.
Predictions: Generating class probabilities for new data and interpreting results.
