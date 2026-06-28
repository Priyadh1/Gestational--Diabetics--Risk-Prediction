# Gestational--Diabetics--Risk-Prediction
Project Overview
This project presents a machine learning-based system for predicting Gestational Diabetes Mellitus (GDM) risk. The original binary dataset was transformed into a multiclass dataset using K-Means clustering and mean imputation.
Multiple machine learning algorithms, including Random Forest, Support Vector Machine (SVM), and XGBoost, were evaluated. XGBoost achieved the best performance and was selected as the final prediction model.
A PyQt5 desktop application was developed to predict patient risk levels as:
* Non-GDM
* A1 GDM (Low Risk)
* A2 GDM (High Risk)
The application also provides a corresponding health recommendation based on the predicted class.

# Repository Contents

* Constant Project Code Final.ipynb – Complete implementation of the project.
* model.pkl – Trained XGBoost model.
* scaler.pkl – Saved feature scaler.
* features.pkl – Saved feature information.
* Gestational Diabetes Binary Dataset.xlsx – Original binary dataset.
* Multiclass Dataset.xlsx – Generated multiclass dataset.
* Project screenshots demonstrating the application interface and prediction results.

# Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* PyQt5

# Dataset

The project is based on the publicly available Gestational Diabetes Mellitus (GDM) dataset from Kaggle. The multiclass dataset was generated from the original binary dataset using clustering techniques.

# Author

Priyadharshini M
M.Sc. Computer Science
