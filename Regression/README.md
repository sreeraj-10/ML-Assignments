# ML- Regression

## Overview
This project performs regression analysis using the California Housing dataset. Several machine learning models are implemented and compared based on their performance.

## Dataset
The dataset is fetched from `sklearn.datasets.fetch_california_housing` and contains house price information for different regions in California.

### Loading and Preprocessing
- Load the dataset from `sklearn.datasets`.
- Handle missing values and perform feature scaling.
- Explanation of preprocessing steps included.

## Models Implemented
1. **Linear Regression** - Fits a straight line; works well for linear data but may not capture complex patterns.
2. **Decision Tree Regressor** - Splits data into decision nodes; good for non-linear relationships but may overfit.
3. **Random Forest Regressor** - Uses multiple trees; reduces overfitting and works well for structured data.
4. **Gradient Boosting Regressor** - Boosts weak models sequentially; highly accurate for structured data.
5. **Support Vector Regressor (SVR)** - Uses hyperplanes; effective for complex patterns but slow for large datasets.

## Evaluation Metrics
The models are evaluated using:
- **Mean Squared Error (MSE)**
- **Mean Absolute Error (MAE)**
- **R-squared Score (R²)**

  ## Results
The comparison of the models is visualized using a bar plot of their R-squared scores.

![Image](https://github.com/user-attachments/assets/07e9b29d-ec3b-4737-8815-3baa5876ad69)


## Requirements

### Tools
- Jupyter Notebook

### Python Libraries
- pandas
- numpy
- matplotlib
- sklearn
- seaborn

## How to Use
1. Clone this repository.
2. Navigate to the project directory.
3. Open and run the project notebook.

## Conclusion
This project demonstrates machine learning classification and regression techniques, evaluating model performance using standard metrics. It serves as a practical guide for implementing predictive models in Python.
