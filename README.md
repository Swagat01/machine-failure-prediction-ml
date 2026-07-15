# machine-failure-prediction-ml
# Machine Broken or Not Prediction Using Machine Learning

## Project Overview
This project uses machine learning techniques to predict whether a machine is **broken or not broken** based on machine sensor data and operational parameters.

The objective is to develop a classification model that can identify machine failures early and support predictive maintenance decisions.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Machine Learning Models Used
- Logistic Regression
- K-Nearest Neighbors (KNN)

## Project Workflow
1. Load the machine maintenance dataset
2. Perform Exploratory Data Analysis (EDA)
3. Handle categorical data using encoding techniques
4. Scale features using StandardScaler/MinMaxScaler
5. Split data into training and testing sets
6. Train classification models
7. Predict whether the machine is broken or not broken
8. Evaluate model performance

## Evaluation Metrics
- Accuracy Score
- Precision
- Recall
- F1 Score
- Classification Report
- Confusion Matrix

## Target Variable
The model predicts:
- **0 → Machine is not broken**
- **1 → Machine is broken**

## Files
- `maintenance_data.csv` - Dataset
- `maintenance_log.ipynb` - Machine learning code
- `README.md` - Project documentation

## Conclusion
This project demonstrates the application of machine learning for predictive maintenance by detecting whether a machine is likely to be broken based on available machine data.
