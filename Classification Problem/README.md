# ML Classification Problem

## Objective
This project applies supervised learning techniques to classify breast cancer cases using machine learning models.

## Dataset
The Breast Cancer dataset from `sklearn.datasets` is used for training and testing classification models.

### 1. Loading and Preprocessing
- Load the dataset from `sklearn.datasets`.
- Handle missing values and perform feature scaling.
- Explanation of preprocessing steps included.

### 2. Classification Algorithm Implementation
Implemented five classification models:
1. **Logistic Regression** - A statistical model for binary classification.
2. **Decision Tree Classifier** - A tree-based approach for decision-making.
3. **Random Forest Classifier** - An ensemble method for improving predictions.
4. **Support Vector Machine (SVM)** - A model that finds the optimal hyperplane for classification.
5. **k-Nearest Neighbors (k-NN)** - A distance-based classifier.

Each model is evaluated based on accuracy, precision, recall, and F1-score.

### 3. Model Comparison
- **Best-performing model:**  Logistic Regression, Random Forest Classifier, and Support Vector Machine (SVM) (Accuracy: 97.37%)
- **Worst-performing model:** Decision Tree Classifier (Accuracy: 93.86%)

![Image](https://github.com/user-attachments/assets/72139767-fd81-49ef-92cb-95530b3d216a)


## 4. Requirements

### Tools
- Jupyter Notebook 

### Python Libraries
- pandas
- numpy
- matplotlib
- sklearn
- seaborn

## 5. Summary
* Logistic Regression, Random Forest Classifier, and Support Vector Machine (SVM) (Accuracy: 97.37%)
* These models provided the highest accuracy, making them the best choices for this dataset.
* Decision Tree Classifier (Accuracy: 93.86%)
* It had the lowest accuracy, likely due to overfitting. Decision trees tend to capture noise in the data, leading to reduced generalization.

## How to Use
1. Clone this repository.
2. Open and run the project notebook.

## Conclusion
This project explores classification techniques and evaluates their performance using standard ML metrics. It serves as a practical guide for implementing classification models in Python.
