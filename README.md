# Kaggle House Prices - Advanced Regression Techniques

This repository contains Python code for predicting house prices using machine learning techniques. The dataset used for training and testing the model is sourced from the Kaggle competition [House Prices: Advanced Regression Techniques.](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

## Project Structure
- house_price_prediction.ipynb: Jupyter Notebook containing the main code for data preprocessing, exploratory data analysis (EDA), and model training.
- train.csv: Training dataset.
- test.csv: Testing dataset.
- submission.csv: CSV file containing the final predictions for the test dataset.
- sample_submission.csv: sample of the file containing the final predictions for the test dataset.

## Dependencies
Ensure you have the required Python libraries installed. You can install them using the following:

```
pip install pandas numpy scipy scikit-learn matplotlib seaborn xgboost catboost lightgbm
```

## How to Run
1. Clone the repository:
```
git clone https://github.com/michael-e-kebede/kaggle_housing_pred.git
```
2. Navigate to the project directory:
```
cd kaggle_housing_pred
```
3. Open and run the Jupyter Notebook house_price_prediction.ipynb for detailed code execution and analysis.

## Model Overview
The predictive modeling includes the following steps:

1. Exploratory Data Analysis (EDA): Understanding the dataset's structure, visualizing distributions, and identifying potential outliers.
2. Data Preprocessing: Handling missing values, removing outliers, and creating new features to improve model performance.
3. Feature Engineering: Creating additional relevant features such as house age, total square footage, total number of bathrooms, etc.
4. Model Training: Utilizing various regression models including Linear Regression, Random Forest, XGBoost, Ridge, Gradient Boosting, LGBM, and CatBoost.
5. Model Evaluation: Evaluating models using mean squared error and selecting the best-performing models.
6. Ensemble Learning: Implementing ensemble methods including Voting Regressor and Stacking Regressor to improve predictive accuracy.

## Results
The final predictions are stored in the submission.csv file, ready for submission to the Kaggle competition. Currently placed 760th in the leaderboard at the time of writing this. 

Feel free to explore the Jupyter Notebook for a step-by-step walkthrough of the code and analysis.

## Credit
[Youtube video](https://www.youtube.com/watch?v=UqmulHG4IvY) by : Ryan Nolan Data
