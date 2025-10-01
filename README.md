# 🌍 World Population Growth Analysis  
![World Population Growth](https://github.com/user-attachments/assets/1fa34510-e3b8-480a-b47d-dbc2ef21a8b8)


This project explores **world population growth trends** using historical data, exploratory data analysis (EDA), visualizations, and machine learning models to forecast population up to **2050**.  

---


## 🔍 Steps in the Analysis  

### 1. Data Preparation  
- Cleaned numeric columns (`Population`, `Yearly Growth %`, `Density`)  
- Converted data types for numerical analysis  
- Checked missing values (none found)  

### 2. Exploratory Data Analysis (EDA)  
- Historical population growth (1950–2023)  
- Yearly percentage change in population  
- Rolling 3-year averages for smoother growth visualization  
- Density trends (population per km²)  

### 3. Visualizations  
- Line plots of global population growth  
- Year-over-year percentage change trends  
- Rolling mean comparison to detect long-term growth patterns  

### 4. Machine Learning Models  
- **Linear Regression**: Captures linear trend with polynomial feature (`Year²`)  
- **Random Forest Regressor**: Captures nonlinear patterns  
- **Features used**:  
  - Year  
  - Year²  
  - Lagged population values (lag-1, lag-2)  

### 5. Forecasting to 2050  
- Used both models to predict future population (2024–2050)  
- Iterative forecasting with lagged values  
- Results show consistent upward growth, though forecasts should be interpreted with caution (extrapolation).  

---

## 📊 Results  

- **Linear Regression**: R² ≈ 0.996, MSE ≈ 1.39e16  
- **Random Forest**: R² ≈ 0.9993, MSE ≈ 2.5e15  
- **Forecast**: Both models project continued growth toward **~9–10 billion by 2050**.  

---


