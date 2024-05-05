# Concrete Strength Regression

This project focuses on analyzing the compressive strength of concrete, a critical factor in civil engineering. The dataset used contains information on various components of concrete mixture and their impact on compressive strength. The objective is to build regression models to predict concrete strength based on the given attributes.

## Key Steps
**1. Initial Analysis**
* Conducted thorough univariate and bivariate exploratory data analysis (EDA) to understand the data distribution and inter-variable relationships.
* Detected and addressed outliers to ensure model accuracy.
  
**2. Model Selection and Training**
* Utilized a range of regression techniques including Linear Regression, Lasso Regression, Ridge Regression, and Random Forest Regression.
* Evaluated models using performance metrics such as Mean Absolute Error (MAE) and R2 Score.
  
**3. Feature Selection**
* Employed various methods including heatmap analysis, Principal Component Analysis (PCA), Recursive Feature Elimination (RFE), and SelectPercentile to identify significant features.
* Selected the most relevant features to enhance model performance.
  
**4. Final Model Selection**
* Re-assessed regression models after feature selection.
* Identified Linear Regression as the most suitable model based on improved accuracy and reduced error metrics.
