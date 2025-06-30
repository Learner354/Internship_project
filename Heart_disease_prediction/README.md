# Task 3: Heart Disease Prediction

## Objective
The objective of this task is to build a binary classification model that predicts whether an individual is at risk of heart disease based on various health-related features.

## Dataset
The **Heart Disease UCI** dataset contains several medical attributes such as age, sex, chest pain type, resting blood pressure, cholesterol levels, and more. The target variable is `1` if the patient has heart disease, and `0` otherwise.

**Source**: [UCI Heart Disease Dataset on Kaggle](https://www.kaggle.com/ronitf/heart-disease-uci)

## Tools and Libraries
- Python 3.x
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

## Workflow Summary

### 1. Data Cleaning
- Checked for and confirmed the absence of missing values.
- Ensured data types were appropriate for modeling.

### 2. Exploratory Data Analysis (EDA)
- Visualized the class distribution of heart disease.
- Plotted a heatmap to examine correlations between features.

### 3. Feature Selection
- Defined `X` as the features and `y` as the target (`target` column).

### 4. Model Training
- Performed train-test split (80/20).
- Trained a **Logistic Regression** model to classify heart disease risk.

### 5. Evaluation Metrics
- **Accuracy Score**: Overall correctness of predictions.
- **Confusion Matrix**: Number of true/false positives and negatives.
- **ROC Curve & AUC**: Model's ability to distinguish between classes.

### 6. Feature Importance
- Analyzed coefficients from logistic regression to determine which features most influenced predictions.

## Skills Demonstrated
- Binary classification using logistic regression
- Medical data interpretation
- Model evaluation using accuracy, ROC-AUC, and confusion matrix
- Feature importance analysis for model transparency

## Results
The model provides a solid foundation for predicting heart disease risk using interpretable features and metrics. ROC curve and confusion matrix help visualize its reliability.

## Future Improvements
- Experiment with other models (e.g., Decision Tree, Random Forest)
- Apply feature scaling and hyperparameter tuning
- Cross-validation for more robust evaluation
