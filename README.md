# Car Prediction Model 🚗💡

## Overview
This repository contains a **Car Price Prediction Model** that estimates the price of second-hand cars based on various features. The project involves data cleaning, exploratory data analysis (EDA), feature engineering, and the implementation of **machine learning models** such as **Linear Regression** and **Random Forest Regressor**.

## Dataset
The dataset includes various attributes of cars, such as:
- Brand
- Model
- Year
- Mileage
- Fuel type
- EngineV
- Body


The dataset was preprocessed to remove inconsistencies, handle missing values, and perform feature scaling where necessary.

## Models Implemented
Two models were trained and evaluated:

1. **Random Forest Regressor** 🌳
   - **Train Performance:**
     - MAE: **77.74**
     - RMSE: **630.18**
     - R² Score: **1.00**
   - **Test Performance:**
     - MAE: **2264.93**
     - RMSE: **4172.37**
     - R² Score: **0.96**

2. **Linear Regression** 📈
   - **Train Performance:**
     - MAE: **5421.25**
     - RMSE: **10165.94**
     - R² Score: **0.76**
   - **Test Performance:**
     - MAE: **5872.92**
     - RMSE: **11692.29**
     - R² Score: **0.72**

## Conclusion
- **Random Forest Regressor** outperformed **Linear Regression**, achieving a higher **R² score** and lower errors, making it the better model for predicting car prices.
- **Linear Regression** showed moderate performance but had higher error margins, indicating non-linearity in the data that was better captured by the Random Forest model.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/FDS-project.git
   ```
2. Navigate to the project folder:
   ```bash
   cd FDS-project
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the notebook:
   ```bash
   jupyter notebook combined_notebook.ipynb
   ```

## Future Enhancements
- Experiment with other regression models such as **XGBoost** and **Gradient Boosting**.
- Optimize hyperparameters to improve model accuracy further.
- Deploy the model using **Flask/Django** or a cloud-based solution.

## Contributors
- **Subham Parajuli**
- **Sadeep Khanal**

## License
This project is licensed under the MIT License.

