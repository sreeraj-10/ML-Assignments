Breast Cancer Classification

Objective

This project aims to classify breast cancer cases using different supervised learning algorithms. The dataset used is the Breast Cancer dataset from the sklearn library.

Dataset

The Breast Cancer dataset consists of features computed from digitized images of breast mass. The features describe the characteristics of the cell nuclei present in the image. The target variable indicates whether the cancer is malignant or benign.

Key Components

1. Loading and Preprocessing

Load the dataset from sklearn.datasets.

Handle missing values (if any) and perform feature scaling.

Split the dataset into training and testing sets.

2. Classification Algorithm Implementation

Implemented five classification models:

Logistic Regression - Works well for binary classification problems.

Decision Tree Classifier - Captures complex patterns but may overfit.

Random Forest Classifier - Reduces overfitting by using multiple decision trees.

Support Vector Machine (SVM) - Effective for high-dimensional spaces.

k-Nearest Neighbors (k-NN) - Simple and intuitive but can be slow for large datasets.

3. Model Evaluation

Evaluate models using Accuracy Score, Classification Report, and Confusion Matrix.

Compare the performance of the five classification algorithms.

Identify the best and worst-performing models.

4. Results & Comparison

The best-performing model: Random Forest Classifier (Highest Accuracy)

The worst-performing model: k-NN Classifier (Lowest Accuracy)

Installation and Usage

Clone the repository:

git clone https://github.com/yourusername/ML-Breast-Cancer-Classification.git
cd ML-Breast-Cancer-Classification

Install dependencies:

pip install -r requirements.txt

Run the Jupyter Notebook:

jupyter notebook ML-Assignment-4-Classification\ Problem.ipynb

Dependencies

The required Python packages are listed in requirements.txt:

numpy
pandas
matplotlib
seaborn
scikit-learn
jupyter

Contributing

Feel free to fork this repository and submit pull requests to improve the project.

License

This project is licensed under the MIT License.


