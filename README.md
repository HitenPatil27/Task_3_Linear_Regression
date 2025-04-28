# Task_3_Linear_Regression 
# Bitcoin (BTC) 2018 Minute Dataset

This project was completed as part of the AI & ML Internship Task 3. The goal is to Implement and understand simple & multiple linear regression.

---

## Dataset
I used the [Bitcoin (BTC) 2018 Minute Dataset](https://www.kaggle.com/datasets/prasoonkottarathil/btcinusd).

---

## Tools & Libraries

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Scikit-learn**
---

## Steps Performed

### 1. Imported Dataset
Imported required libraries like pandas, matplotlib, scikit-learn modules & Loaded the BTC-2018min.csv file.

### 2. reprocessing
- Selected Open as the independent variable and Close as the dependent variable.
- Checked for missing values (there were none).

### 3. Data Splitting
- Split the data into training and testing sets (80% training, 20% testing).

### 4. Model Training
- Used LinearRegression() from scikit-learn to fit the model on training data.

### 5. Model Evaluation
Evaluated the model using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

### 6. Visualization
- Plotted the actual vs predicted close prices.
- Displayed the regression line over the data points.

### 7. Interpretation
- Printed the model's intercept and slope.
- Interpreted how much the Close price changes with respect to the Open price.

---

## Results
- Mean Absolute Error (MAE): (e.g., ~1.2345)
- Mean Squared Error (MSE): (e.g., ~2.3456)
- R² Score: (e.g., ~0.9876)


