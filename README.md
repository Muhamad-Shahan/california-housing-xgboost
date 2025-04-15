# california-housing-xgboost
# California Housing Price Prediction Using XGBoost

## 📌 Project Overview
This project focuses on predicting housing prices in California using the XGBoost regression algorithm. The dataset used is the California Housing dataset, which includes features such as median income, housing age, and geographical information. The objective is to build a high-performing model through effective preprocessing, feature selection, and hyperparameter tuning.

---

## 📊 Dataset
The dataset contains housing information for various districts in California and includes the following features:

- `MedInc`: Median income in block group
- `HouseAge`: Median house age in block group
- `AveRooms`: Average number of rooms per household
- `AveBedrms`: Average number of bedrooms per household
- `Population`: Block group population
- `AveOccup`: Average house occupancy
- `Latitude` and `Longitude`: Block group coordinates
- `Target`: Median house value (target variable)

---

## 🛠️ Tools & Technologies
- Python  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Scikit-learn  
- XGBoost  

---

## 🚀 Project Workflow
1. **Data Exploration & Visualization**  
   - Understanding data distribution and relationships through plots and correlation matrices.

2. **Data Preprocessing**  
   - Handling missing values  
   - Feature scaling  
   - Outlier detection (optional)

3. **Modeling with XGBoost**  
   - Train-test split  
   - Model training using XGBoost Regressor  
   - Hyperparameter tuning with GridSearchCV or RandomizedSearchCV

4. **Model Evaluation**  
   - Mean Absolute Error (MAE)  
   - Mean Squared Error (MSE)  
   - Root Mean Squared Error (RMSE)  
   - R² Score

5. **Result Visualization**  
   - Prediction vs Actual value plots  
   - Residual error plots

---

## 📈 Results
The XGBoost model achieved strong predictive performance and effectively captured non-linear relationships in the data. Hyperparameter tuning further improved model accuracy and reduced overfitting.

---


