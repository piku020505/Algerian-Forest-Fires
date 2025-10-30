# Algerian-Forest-Fires
# Algerian Forest Fire Prediction Model

This project focuses on predicting the occurrence and intensity of forest fires in Algeria using machine learning. It involves data cleaning, exploratory data analysis (EDA), feature engineering, and model training using regression algorithms.

## 📊 Project Overview

The Algerian forest fire dataset provides meteorological and fire weather index parameters recorded across different regions of Algeria. The goal of this project is to develop a predictive model capable of identifying high-risk fire zones based on environmental data.

## 🧠 Key Steps

1. **Data Preprocessing:**  
   - Handled missing values and data inconsistencies  
   - Normalized input features using `StandardScaler`  

2. **Exploratory Data Analysis (EDA):**  
   - Visualized trends and correlations between temperature, humidity, wind, and fire risk  
   - Identified significant predictive variables through feature importance  

3. **Model Training:**  
   - Implemented and compared multiple regression models  
   - Finalized **Ridge Regression** for optimal performance  
   - Saved model and scaler as `.pkl` files for deployment  

## 🧾 Dataset

- **Source:** Algerian Forest Fire Dataset (UCI Machine Learning Repository)  
- **Features:** Temperature, RH, Wind, Rain, and Fire Weather Index (FWI)  
- **Target:** Fire occurrence and severity levels  

## ⚙️ Tech Stack

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Jupyter Notebook  

## 📈 Results

- Achieved high predictive accuracy on test data  
- Model successfully identifies patterns that indicate fire-prone conditions  

## 🚀 Future Improvements

- Integrate real-time weather data APIs  
- Deploy as a web dashboard or REST API for live prediction  


