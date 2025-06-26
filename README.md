# PROJECT 3
## House Price Prediction – Data Analysis & Linear Regression
    This project focuses on predicting house prices using exploratory data analysis (EDA), preprocessing, feature encoding, scaling, outlier handling, and a linear regression model.

## Dataset Overview & Initial Checks
    - Imported essential libraries: numpy, pandas, matplotlib, seaborn.
    - Displayed dataset structure using .head(), .tail(), .info(), .describe(), .shape.
    - Checked for missing values and duplicate entries.

## Data Preprocessing
    - Applied LabelEncoder to convert categorical features (mainroad, guestroom, etc.) into numeric format.
    - Used get_dummies() for one-hot encoding on furnishingstatus.

## Feature Scaling
    - Performed Min-Max Normalization and Standard Scaling on numerical columns to bring values into a comparable range.

## Exploratory Data Analysis (EDA)
    - Plotted a correlation heatmap to identify relationships between variables.
    - Visualized distributions of key numerical features like price, area, bedrooms, etc.
    - Used box plots to identify and visualize outliers in price and area.

## Outlier Handling
    - Applied IQR method to detect outliers.
    - Replaced outliers in price and area with their respective column means.

## Model Preparation
    - Defined feature matrix X and target variable y (house price).
    - Split data into training (80%) and testing (20%) sets using train_test_split.

## Model Training – Linear Regression
    - Built and trained a Linear Regression model on the training data.
    - Printed model intercept and coefficients for interpretation.

## Model Evaluation
    - Calculated Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² Score to evaluate prediction performance.
    - Visualized the model by plotting actual vs predicted house prices based on area.

##  Conclusion
    - This project demonstrates a complete machine learning pipeline:
    - Data cleaning
    - Preprocessing
    - Visualization
    - Outlier handling
    - Model training and evaluation
    - The linear regression model provides a good baseline for housing price prediction.

## Tools & Libraries Used
    -Python 3.x
    - Pandas, NumPy
    - Matplotlib, Seaborn
    - Scikit-learn