# Logistic Regression with Python

## Overview
This project involves implementing Logistic Regression to classify survival outcomes based on the Titanic dataset from Kaggle. The goal is to predict whether a passenger survived or did not survive the Titanic disaster using a range of features from the dataset.

## Libraries Used
- `pandas` (for data manipulation)
- `numpy` (for numerical operations)
- `matplotlib` (for plotting)
- `seaborn` (for data visualization)
- `scikit-learn` (for machine learning models and evaluation)

## Data
The dataset used is a "semi-cleaned" version of the Titanic dataset. It includes features such as passenger class, age, fare, and embarked location. The dataset is loaded from the `titanic_train.csv` file.

## Analysis Steps
1. **Import Libraries**: Necessary libraries are imported to handle data and perform machine learning tasks.
2. **Load Data**: The Titanic dataset is read into a pandas DataFrame.
3. **Exploratory Data Analysis (EDA)**: 
   - Missing data is visualized.
   - Data distributions and relationships are explored using plots.
4. **Data Cleaning**:
   - Missing values in age are imputed based on passenger class.
   - Unnecessary columns are dropped.
   - Categorical features are converted into dummy variables.
5. **Model Building**:
   - The dataset is split into training and test sets.
   - A Logistic Regression model is trained on the data.
6. **Model Evaluation**:
   - The model's performance is assessed using precision, recall, and f1-score metrics.

## Insights
- Logistic Regression effectively classifies survival outcomes based on the features provided.
- Proper data cleaning and feature transformation are crucial for achieving accurate predictions.

## Conclusion
The project demonstrates how to use Logistic Regression for binary classification tasks. By preprocessing the Titanic dataset and applying Logistic Regression, we can predict survival outcomes with reasonable accuracy. This approach can be adapted to other classification problems with similar data structures.

## Requirements
To run this project, you need to install the following Python libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

You can install these libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
