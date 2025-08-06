# House Sale Price Prediction using Linear Regression

This project aims to build a *Linear Regression model* that predicts house prices based on features such as square footage, number of bedrooms, and bathrooms. 

It was completed as part of an internship task to apply machine learning concepts using real-world housing data.

---

## Dataset

**Source**: [Kaggle - House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)

---

## Tools & Libraries Used

* Core programming language used : **Python** 
* Libraries and Frameworks: **Pandas,Numpy,Matplotlib ans Seaborn,Scikit-learn**

### Purpose of each tool:
- **Scikit-learn** For building the linear regression model, standardizing data, splitting the dataset, and evaluating performance
- **Pandas** and **NumPy** For reading and manipulating CSV files and for numerical computations
- **Matplotlib** for plotting visualizations.
- **Seaborn** to enhances visualizations.

---

## Standard tasks performed during the project: 

1. **Data Preprocessing**
   - Selected only relevant features: `GrLivArea`, `BedroomAbvGr`, and `FullBath`
   - Standardized features using `StandardScaler`
   - Handled skewed data by applying `log1p()` on `SalePrice`

2. **Model Building**
   - Trained a **Linear Regression** model on the training set
   - Evaluated it using **Mean Squared Error (MSE)** and **R² Score**

3. **Prediction & Visualization**
   - Made predictions on the validation and test sets
   - Visualized **Actual vs Predicted** sale prices using a scatter plot

---

## Results

- **Model Coefficients** and **Intercept** were printed to interpret the model.
- **R² Score** of ~0.64 ,explaining 64% of the variation of SalePrice


---

## What I Learned

- How to build a regression model using **scikit-learn**
- The importance of **feature selection** and **preprocessing** in machine learning
- How to handle **skewed data** using log transforms
- How to **visualize model performance** effectively
- The impact of **standardization** and when it's necessary


---


## Acknowledgements

Thanks to the [Kaggle community](https://www.kaggle.com/) for hosting this dataset and challenge, and to my internship mentor for this opportunity to apply machine learning to a real dataset.
