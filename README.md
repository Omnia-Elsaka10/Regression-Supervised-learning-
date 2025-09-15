# ✈️ Regression Projects  

This repo contains three regression assignments and one case study project on **Flight Price Prediction**.  

---

## 📘 Assignment 1 – Simple Linear Regression
- Equation: `y = 2x + 7 + noise`  
- Learned slope ≈ **2.09**, intercept ≈ **6.05**  
- Performance:  
  - Train R² = 0.94  
  - Test R² = 0.91  
- ✅ Model generalized well (no overfitting/underfitting).  

---

## 📘 Assignment 2 – Multiple Linear Regression
- Equation: `y = 2·x₁ + 3·x₂ + 5 + noise`  
- Learned coefficients ≈ **[2.53, 2.53]**, intercept ≈ **8.91**  
- Performance:  
  - Train R² = 0.993  
  - Test R² = 0.991  
- ✅ Excellent fit, coefficients close to original.  

---

## 📘 Assignment 3 – Polynomial Regression
- Equation: `y = 0.5x² + 2x + 3 + noise`  
- Used `PolynomialFeatures(degree=2)`  
- Performance:  
  - Train R² = 0.987  
  - Test R² = 0.976  
- ✅ Model captured the non-linear relationship well.  

---

## ✈️ Flight Price Prediction (Case Study)
- **Dataset:** ~300k rows, 12 features (airline, source, destination, stops, class, duration, days_left, price).  
- **Steps:**  
  - EDA: distributions, correlations, outliers.  
  - Data cleaning: removed extreme outliers (duration > 26 hrs, price > 10k).  
  - Preprocessing: scaling numeric features, one-hot encoding categorical.  
  - Modeling: Linear Regression.  
- **Results:**  
  - Train R² = 0.44, Test R² = 0.44  
  - MAE ≈ 1130 INR  
- ⚠️ Model underfits → next step is trying **Random Forest, Gradient Boosting, XGBoost**.  

---

## 🔮 Future Work  
- Improve Flight Price Prediction using ensemble models.  
- Apply feature engineering (e.g., time of day, holidays).  
- Hyperparameter tuning with cross-validation.  
