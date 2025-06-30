# Task 6: House Price Prediction

## Objective
The objective of this task is to predict house prices based on property features such as size, number of bedrooms, and location using regression techniques. This project demonstrates the full pipeline from data preprocessing to model evaluation and visualization.

## Dataset
The dataset used is the **USA Housing Dataset**, which includes features such as:
- `Avg. Area Income`
- `Avg. Area House Age`
- `Avg. Area Number of Rooms`
- `Avg. Area Number of Bedrooms`
- `Area Population`
- `Price` (target variable)
- `Address` (excluded from modeling)

## Tools and Libraries
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Workflow Summary

### 1. Data Preprocessing
- Checked for and confirmed no missing values.
- Dropped irrelevant columns like `Address`.
- Defined `X` (features) and `y` (target: `Price`).

### 2. Model Training
- Split the dataset into training and test sets using an 80/20 ratio.
- Trained a **Linear Regression** model using scikit-learn.

### 3. Prediction and Visualization
- Made predictions on the test set.
- Plotted a scatter plot comparing actual vs predicted house prices.
- Added a red diagonal reference line for ideal predictions.

### 4. Model Evaluation
- Evaluated model performance using:
  - **Mean Absolute Error (MAE)**
  - **Root Mean Squared Error (RMSE)**

## Results
The model provided a good baseline for house price prediction using basic features. Visualization helped assess prediction accuracy, and evaluation metrics quantified the model’s effectiveness.

## Skills Demonstrated
- Regression modeling with scikit-learn
- Data cleaning and preprocessing
- Evaluation using MAE and RMSE
- Data visualization for model validation

## Next Steps
- Try more complex models (e.g., Gradient Boosting, Random Forest)
- Apply feature scaling or transformation
- Perform cross-validation for more robust evaluation
