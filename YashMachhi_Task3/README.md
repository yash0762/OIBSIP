# Task 3: Car Price Prediction with Machine Learning

**Name:** Yash Machhi  
**Internship:** Oasis Infobyte (OIBSIP)  
**Track:** Data Science  

---

## 📌 Project Overview
This project focuses on building a Supervised Machine Learning regression pipeline to predict the continuous market selling price of used vehicles based on multi-variable criteria such as fuel type, odometer mileage, age, transmission configuration, and seller dealer networks.

## 📂 Folder Files
* `car data.csv` - The used car specifications dataset.
* `YashMachhi_Task3.ipynb` - My Python data cleaning, feature engineering, and model pipeline notebook.
* `actual_vs_predicted_car_prices.png` - Scatter plot model tracking residuals.
* `README.md` - Core project documentation.

## 🤖 Methodology & Engineering Workflow
1. **High Cardinality Management:** Dropped individual labels like `Car_Name` to prevent unique labels from overfitting the model.
2. **Feature Encoding Pipeline:** Configured a Scikit-Learn `ColumnTransformer` to automatically apply a `OneHotEncoder(drop='first')` to string metrics (`Fuel_Type`, `Selling_type`, `Transmission`) ensuring mathematical compatibility.
3. **Model Strategy:** Utilized a **Linear Regression** model fitted over an 80/20 train-test structural split to predict real prices vs. predicted evaluation ranges.

---
*Submitted for the AICTE Oasis Infobyte Virtual Internship Program.*