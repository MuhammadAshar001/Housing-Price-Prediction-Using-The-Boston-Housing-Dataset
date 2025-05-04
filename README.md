# Housing Price Prediction
This project implements a housing price prediction system using a dataset of residential property features to predict housing prices through machine learning and custom regression models.

## Features

Data preprocessing: Handles missing values with median imputation and normalizes features using StandardScaler.
Trains models: Custom Linear Regression (Gradient Descent), Random Forest, and XGBoost.
Evaluates models using MSE, RMSE, and R² Score.
Visualizes feature importance for Random Forest and XGBoost to identify key predictors.


## Tools & Libraries

Python
Pandas, NumPy
Scikit-learn (train-test split, StandardScaler)
Matplotlib, Seaborn
Custom implementations for Linear Regression, Decision Tree, and XGBoost


## Final Results

Model Performance:
Custom Linear Regression: Provides baseline performance using gradient descent.
Random Forest: Improves accuracy with ensemble learning, robust to overfitting.
XGBoost: Achieves highest accuracy and generalization due to boosting.


Key Insight: Features like RM (average number of rooms) and LSTAT (percentage of lower-status population) are critical predictors.


## How to Run

Clone the repository:git clone https://github.com/your-username/housing-price-prediction.git
cd housing-price-prediction


Install the required libraries:pip install -r requirements.txt


Run the notebook:
For Jupyter: Open task4.ipynb and run all cells.




## Input

Dataset: HousingData.csv (features: CRIM, ZN, INDUS, CHAS, NOX, RM, AGE, DIS, RAD, TAX, PTRATIO, B, LSTAT; target: MEDV)


## Output

Evaluation metrics (MSE, RMSE, R² Score) for all models.
Feature importance plots for Random Forest and XGBoost.


## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your suggested improvements.

## License
This project is open-source and available under the MIT License.

