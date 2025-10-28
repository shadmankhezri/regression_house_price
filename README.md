# House Price Prediction

This project demonstrates predicting house prices using Linear Regression and Polynomial Regression in Python. The dataset contains information about houses including:

- Area (in square meters)
- Number of rooms
- Parking availability
- Elevator
- Warehouse
- Address
- Price (in local currency and USD)

## Steps Performed

1. **Data Exploration:** Checked data types, null values, and basic statistics.
2. **Data Cleaning:** Removed null values and outliers, converted data types, and encoded categorical features.
3. **Normalization:** Scaled all numerical features between 0 and 1.
4. **Correlation Analysis:** Identified features correlated with house price.
5. **Model Building:**
   - Linear Regression
   - Polynomial Regression (degree=3)
6. **Evaluation:** Calculated Mean Squared Error (MSE) and R-squared (R²).

## Results

- **Linear Regression:** MSE = 0.0027, R² ≈ 0.63
- **Polynomial Regression:** MSE = 0.00163, R² ≈ 0.78

Polynomial Regression showed better accuracy in predicting house prices compared to Linear Regression.

## Libraries Used

- pandas, numpy
- matplotlib, seaborn
- scikit-learn
