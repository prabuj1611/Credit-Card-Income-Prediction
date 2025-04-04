# Credit-Card-Income-Prediction
Supervised Learning: Simple &amp; Multiple Linear Regression with Credit Card Data

# Credit Card Income Prediction: Simple & Multiple Linear Regression

##  Overview

This repository contains an **analysis of credit card data** using **Simple Linear Regression (SLR) and Multiple Linear Regression (MLR)** to predict **income** based on various numerical attributes. 

The analysis is divided into **two parts**:
1. **Simple Linear Regression (SLR)** - Exploring the relationship between **dependents** and **income**.
2. **Multiple Linear Regression (MLR)** - Building a predictive model using multiple numerical variables.

This project is part of a **Supervised Machine Learning assignment**, focusing on **regression analysis**, **feature selection**, and **model evaluation**.

---

##  Dataset: `CreditCard.csv`

The dataset contains financial and demographic details related to credit card holders. It includes:
- **Income** (target variable)
- **Dependents** (spouse & children under care)
- **Other numerical & categorical attributes** related to credit card usage

---

##  Tasks & Implementation

### **Part 1: Simple Linear Regression**
1. **Data Exploration**
   - Load & describe dataset
   - Identify number of rows & columns

2. **Data Partitioning**
   - Using a seed (last 3 digits of BU ID) to **split data into 60% training & 40% validation**

3. **Exploratory Data Analysis (EDA)**
   - Scatterplot of **Income (y-axis) vs. Dependents (x-axis)**
   - Fit a **best-fit line** on training data
   - Compute & interpret **correlation between income & dependents**

4. **Simple Linear Regression Model**
   - Train a **SLR model** using `sklearn`
   - Compute **model residuals**
   - Identify **highest & lowest residual cases**

5. **Analysis & Limitations**
   - Discuss why **dependents alone** may not perfectly predict **income**.

---

### **Part 2: Multiple Linear Regression**
1. **Feature Selection**
   - Create a **correlation table** for all numerical predictors.
   - Identify potential **multicollinearity issues**.
   - Remove highly correlated variables using **backward elimination**.

2. **Train the MLR Model**
   - Fit a **multiple linear regression model**.
   - Use **`statsmodels` or `sklearn`** for regression analysis.

3. **Model Evaluation**
   - Compute **SST (Total Sum of Squares)**.
   - Compute **SSR (Sum of Squares due to Regression)**.
   - Interpret **regression coefficients & significance**.

---

##  Tech Stack

- **Python** 
- **Pandas** (`pandas`)
- **NumPy** (`numpy`)
- **Matplotlib & Seaborn** (`matplotlib`, `seaborn`) for visualization
- **Scikit-Learn** (`sklearn`) for regression models
- **Statsmodels** (`statsmodels`) for statistical analysis

---

##  Key Results & Observations

- The correlation between **dependents & income** is **weak**, meaning **other factors influence income more**.
- The **Multiple Linear Regression (MLR) model** provided **better predictions** by including more variables.
- Identified **limitations** of predicting income based on numeric attributes alone.

---

##  Future Improvements

- **Incorporate categorical variables** (e.g., job type, education level) using **one-hot encoding**.
- **Use polynomial regression** to capture **non-linear relationships**.
- **Test feature engineering** to derive better predictive features.

---

##  References

- **Supervised Machine Learning** course materials
- **Scikit-Learn documentation**: https://scikit-learn.org
- **Statsmodels documentation**: https://www.statsmodels.org

---

##  Author

**Prabu Jeyabalan**  


---

