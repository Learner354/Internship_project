
# Task 1: Exploring and Visualizing the Credit Card Fraud Detection Dataset

## Objective
This task aims to develop skills in loading, inspecting, and visualizing a real-world dataset to understand patterns, distributions, and detect anomalies. The Credit Card Fraud Detection dataset has been used in place of the Iris dataset.

## Dataset Description
The dataset contains credit card transactions made by European cardholders in September 2013. It includes 284,807 transactions, among which 492 are frauds. Features `V1` to `V28` are the result of a PCA transformation, while `Time` and `Amount` are original features. The `Class` variable indicates whether a transaction is fraudulent (`1`) or legitimate (`0`).

**Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)

## Tools and Libraries
- Python 3.x
- pandas
- matplotlib
- seaborn

## Tasks Performed

### 1. Data Loading and Inspection
- Loaded the dataset using `pandas.read_csv()`
- Printed:
  - Dataset shape
  - Column names
  - First five rows using `.head()`
- Used `.info()` to check data types and nulls
- Used `.describe()` for summary statistics

### 2. Data Visualization
#### Scatter Plots
- Plotted `Amount` vs `Time`, `V1` vs `V2` to observe transaction trends

#### Histograms
- Created histograms for features like `Amount`, `Time`, and `V1`–`V5` to view distribution

#### Box Plots
- Used box plots to detect outliers in features like `Amount`, `V1`, and `V2`

### 3. Observations
- Data is highly imbalanced (fraud cases are less than 0.2%)
- Several features show skewed distributions
- Box plots revealed notable outliers, especially in `Amount` and PCA components

## Skills Demonstrated
- Data loading and inspection using pandas
- Statistical exploration and summary using `.describe()` and `.info()`
- Plotting and visualizing using seaborn and matplotlib
- Detecting outliers and understanding class imbalance

## Conclusion
The Credit Card Fraud Detection dataset provided a practical scenario to explore data, detect anomalies, and understand real-world data distribution challenges. Visualizing skewed data and class imbalance was essential in grasping the nuances of fraud detection.
