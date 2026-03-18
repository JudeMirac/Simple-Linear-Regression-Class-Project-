# Simple Linear Regression Class Project

## Project Overview
This project is focused on implementing a Simple Linear Regression algorithm to analyze and predict outcomes based on given datasets. The methodology employed not only demonstrates the linear regression process but also emphasizes important statistical concepts that underlie the model's application.

## Assignment Requirements (DS 640 Assignment 2)
The project adheres to the following key requirements:

1. **Read CSV File:** The dataset is loaded from a CSV file using Python's pandas library.
   - Data source: USA Housing dataset
   - Loaded using `pd.read_csv()`

2. **Pairplot of Independent Variables:** Visual representations of relationships between variables are created using pairplots from the seaborn library to help visualize correlations between all features and the target variable (Price).

3. **Intercept and Coefficients:** The calculation of the regression equation's intercept and coefficients is performed to interpret the relationship between independent and dependent variables.
   - Linear equation: Price = intercept + (coef₁ × Avg. Area Income) + (coef₂ × Avg. Area House Age) + (coef₃ × Avg. Area Number of Rooms) + (coef₄ × Avg. Area Number of Bedrooms) + (coef₅ × Area Population)

4. **Residual Distribution Histogram:** Residuals are plotted on a histogram to analyze their distribution and check homoscedasticity (equal variance of errors).

5. **Error Metrics:** The project calculates various error metrics to evaluate model performance:
   - **Mean Absolute Error (MAE):** Average of absolute differences between predicted and actual values
   - **Mean Squared Error (MSE):** Average of squared differences between predicted and actual values
   - **Root Mean Squared Error (RMSE):** Square root of MSE, in original units of the target variable

## Dataset
The project uses the **USA Housing dataset** which includes the following features:
- **Avg. Area Income:** Average income of the area
- **Avg. Area House Age:** Average age of houses in the area
- **Avg. Area Number of Rooms:** Average number of rooms
- **Avg. Area Number of Bedrooms:** Average number of bedrooms
- **Area Population:** Population of the area
- **Price:** The target variable (house prices)

## Technologies Used
- **Python 3**: Programming language
- **Pandas**: Data manipulation and CSV reading
- **NumPy**: Numerical computing and vectorized operations
- **Scikit-learn**: Machine learning library for linear regression
- **Matplotlib & Seaborn**: Data visualization libraries

## Project Structure
- `Predictive_Modeling_Assignment.ipynb`: Main Jupyter notebook containing all code, visualizations, and analysis
- `LICENSE`: Project license file
- `README.md`: This file

## Getting Started
To run this project, ensure you have the required libraries installed:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

Then open the Jupyter notebook and run all cells to see the analysis and model results.
