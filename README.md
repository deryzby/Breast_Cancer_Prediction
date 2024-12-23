# Breast Cancer Prediction

This project, titled **Breast_Cancer_Prediction**, utilizes a dataset from Kaggle to predict the diagnosis of breast cancer based on features such as radius, texture, perimeter, and area. The diagnosis is classified as:
- `M`: Malignant
- `B`: Benign

In addition to prediction, this project includes examples of various data science techniques and machine learning models taught in data science courses. These include:

## Implemented Models and Techniques

1. **Linear Regression**
2. **K-Means Clustering (kmeans)**
3. **K-Nearest Neighbors (KNeighborsClassifier)**
4. **XGBoost Classifier (XGBClassifier)**
5. **Logistic Regression**
6. **Decision Tree Classifier**
7. **Confusion Matrix Analysis**
   - Confusion matrices for Logistic Regression and Decision Tree Classifier.

## Dataset Information

The dataset consists of various measurements of breast tissue characteristics, including:
- `radius_mean`
- `texture_mean`
- `perimeter_mean`
- `area_mean`
- And more.

The target variable is `diagnosis`, which indicates whether the case is malignant (`M`) or benign (`B`).

## Requirements

To run this project, ensure you have Python installed and the following libraries:

- `pandas`
- `numpy`
- `scikit-learn`
- `xgboost`
- `matplotlib`
- `seaborn`

Install the dependencies using the command:
```bash
pip install -r requirements.txt
