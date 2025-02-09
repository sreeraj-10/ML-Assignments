# ML - Clustering   

## Objective
This project aims to model car prices based on various independent variables. The model helps management understand how different factors influence car prices, enabling them to adjust car designs and business strategies accordingly.

## Dataset 
The dataset used in this project contains information about various car specifications and their corresponding prices. Key attributes include:
* Engine size
* Horsepower
* Fuel type
* Car dimensions
* Drive wheel type
* Highway and city mileage

## Implementation
### 1. Data Preprocessing:
- Load the dataset
- Removal of irrelevant columns (car_ID, CarName)
- Encoding categorical variables
- Standardizing numerical features
- Splitting data into training and testing sets

### 2. Model Implementation:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- Support Vector Regressor (SVR)
- 
### 3. Model Evaluation:
* Performance measured using:
- R-Squared (R²)
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- Best model identified based on evaluation metrics

### 4. Feature Importance Analysis:
- Identified the most significant variables affecting car prices
   
### 5. Hyperparameter Tuning:
 - Optimized the best-performing model using Grid Search or Random Search

## Results
- Best Model: Random Forest → High accuracy (R² = 0.958), handles non-linearity, reduces overfitting, and gives the lowest errors.

- Worst Model: Support Vector Regressor → Poor fit (R² = -0.099), struggles with complex data, and has the highest prediction errors.

- Engine size & curb weight are the most crucial factors for car pricing

## Requirements

### Tools
- Jupyter Notebook 

### Python Libraries
- pandas
- numpy
- sklearn

## How to Use
1. Clone this repository.
2. Open and run the project notebook.

## Conclusion
This project successfully implemented and evaluated multiple regression models to predict car prices. Among them, Random Forest Regressor emerged as the best model with high accuracy (R² = 0.958) and low error rates.
