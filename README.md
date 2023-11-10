# House Price Prediction using Machine Learning

## Overview
This project focuses on creating a machine-learning model for predicting house prices. The dataset used for training the model contains 13 features, including information about the type of dwelling, lot size, overall condition, and various other factors.

## Tools Used
- Python
- Libraries: pandas, matplotlib, seaborn, sci-kit-learn

## Dataset Information
- **Features:**
  - Id: Record identifier
  - MSSubClass: Type of dwelling
  - MSZoning: Zoning classification
  - LotArea: Lot size in square feet
  - ... (other features)

## Data Exploration and Analysis
- Utilized pandas, matplotlib, and seaborn for data analysis and visualization.
- Explored correlations between features using a heatmap.

## Data Cleaning
- Dropped irrelevant columns (e.g., 'Id').
- Handled missing values by dropping records and filling null values in the 'SalePrice' column with the mean.

## Exploratory Data Analysis (EDA)
- Conducted EDA to analyze categorical features, unique values, and distributions.

## Data Preprocessing
- Applied OneHotEncoding to convert categorical features into binary vectors.

## Model Training and Evaluation
- Split the dataset into training and testing sets.
- Trained three regression models: SVM, Random Forest, and Linear Regression.
- Evaluated models using mean absolute percentage error.

## Model Comparison
- SVM demonstrated the best accuracy with the lowest mean absolute percentage error.

## Conclusion
This project showcases the application of machine learning techniques to predict house prices. The SVM model, in particular, exhibited superior performance. Further improvements could be explored using ensemble learning techniques like Bagging and Boosting.

For detailed implementation, refer to the Python script or Jupyter notebook in this repository.
