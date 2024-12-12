House Price Prediction

This repository contains a machine learning project that predicts house prices using the California Housing dataset. The implementation utilizes Python and popular libraries for data processing, visualization, and machine learning.

Overview

The project aims to predict house prices based on features such as population, median income, and housing characteristics. The following steps are implemented:

Data Loading: The California Housing dataset is fetched using fetch_california_housing from sklearn.

Data Preprocessing: Missing values are checked, and a new column for the target variable (price) is added.

Exploratory Data Analysis (EDA): The dataset is visualized using correlation heatmaps.

Data Splitting: The data is divided into training and testing sets using train_test_split.

Model Training: An XGBRegressor model is trained on the training data.

Evaluation: The model’s accuracy is evaluated on the training data.
