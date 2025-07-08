
# Retail Sales Forecasting with Walmart Data | Python, ML

A data-driven project focused on retail sales analysis and forecasting for Walmart using Python. This project answers key business questions using exploratory data analysis (EDA) and predictive modeling.

---

## Table of Contents
1. [Project Motivation](#motivation)
2. [Installation & Tools](#installation)
3. [Dataset Overview](#dataset)
4. [Implementation & Modeling](#implementation)
5. [Results & Insights](#results)
6. [Connect With Me](#connect)

---

## 1. Project Motivation <a name="motivation"></a>

This project aims to understand and forecast Walmart's retail performance. Business questions explored:

- Which stores have the highest sales?
- Which stores show high sales volatility (standard deviation)?
- Which stores saw significant growth in Q3 of 2012?
- Do holidays increase sales over non-holiday periods?
- What are the monthly and semester-wise sales trends?
- Can we build machine learning models to predict future sales?

---

## 2. Installation & Tools <a name="installation"></a>

Install the required libraries using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

**Tools Used:**
- Python 3.8+
- Pandas, NumPy for data manipulation  
- Matplotlib, Seaborn for visualization  
- scikit-learn for regression models  
- datetime for date-related transformations

---

## 3. Dataset Overview <a name="dataset"></a>

- Source: [Kaggle - Retail Walmart Dataset](https://www.kaggle.com/aditya6196/retail-analysis-with-walmart-data)  
- Data from **45 Walmart stores**
- Time period: **2010-02-05 to 2012-11-01**
- Key features: Store, Weekly_Sales, Holiday_Flag, Temperature, Fuel_Price, CPI, Unemployment, Date

---

## 4. Implementation & Modeling <a name="implementation"></a>

### Data Processing
- Handled missing values  
- Feature engineering (Quarter, Month, Semester)  
- Aggregated weekly data into monthly and semester views  

### Models Used
- [Linear Regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html)  
- [Random Forest Regressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html)  

**Train/Test Split:** 80/20 ratio  
**Evaluation Metrics:** R² score, MAE, RMSE

---

## 5. Results & Insights <a name="results"></a>

- Store 20 recorded the **highest total sales** across the period  
- Store 14 showed the **highest standard deviation**, indicating variable performance  
- Store 4 had the **highest Q3 2012 growth**  
- Certain holidays like **Labor Day** and **Super Bowl** saw higher-than-average sales  
- Sales tend to **peak in December** and **dip mid-year**  
- **Random Forest** outperformed Linear Regression in terms of accuracy and RMSE

Visual insights and prediction outputs are detailed in the notebook.

---

## 6. Connect With Me <a name="connect"></a>

**Vaibhav Gupta** – B.Tech, IIT Mandi  
[![GitHub](https://img.shields.io/badge/GitHub-vaibhav230104-black?logo=github)](https://github.com/vaibhav230104)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/vaibhav-gupta-b6603025b/)

---

> This project combines business-focused analysis with predictive modeling to offer valuable insights into retail dynamics.
