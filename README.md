# Assignment1

Titanic Survival Prediction

Project Overview

This project focuses on predicting passenger survival on the Titanic using machine learning techniques. The dataset used is the Titanic dataset, which includes passenger details such as age, sex, class, and fare. The notebook performs essential data preprocessing steps to prepare the data for modeling.

The Titanic Survival Prediction project employs a structured data preprocessing pipeline to prepare the Kaggle Titanic dataset for analysis. Initially, the dataset is imported using pandas, followed by an exploratory analysis to assess its structure, data types (df.dtypes), and missing values (df.isnull().sum()). Missing values are addressed by imputing Age with the mean or median, filling Embarked with the mode, and handling Cabin by extracting the deck (first letter) and imputing missing entries. Categorical features, such as Sex and Embarked, are converted to numerical values using label encoding or one-hot encoding to ensure compatibility with machine learning algorithms. Numerical features like Age and Fare are standardized using scikit-learn's StandardScaler to normalize their scales. Finally, outliers in numerical features are visualized using seaborn boxplots and removed based on thresholds, such as the interquartile range method, to enhance data quality. This methodology ensures a clean, well-prepared dataset ready for further feature engineering or model development.
