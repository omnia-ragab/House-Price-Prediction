# House-Price-Prediction
A Machine Learning project to predict housing prices using Regression techniques. Includes data cleaning, exploratory data analysis (EDA), and model evaluation using Scikit-learn"
ر# 🏡 California Housing Price Predictor 


##  Project Overview
This project predicts the **Median House Value** in California using various features like income, location, and housing age. It’s an end-to-end Machine Learning project covering everything from data exploration to model deployment.

##  Key Features
*   **Deep EDA:** Comprehensive data analysis using `ydata-profiling` to understand distributions and correlations.
*   **Feature Engineering:** Created new meaningful features like `rooms_per_household` and `bedrooms_ratio` to boost model accuracy.
*   **Hyperparameter Tuning:** Optimized the Random Forest model using `GridSearchCV` to find the best `n_estimators` and `max_depth`.
*   **Interactive Web App:** A user-friendly interface built with **Streamlit** for real-time price predictions.

##  Tech Stack
*   **Analysis:** Pandas, NumPy, Matplotlib, Seaborn.
*   **Machine Learning:** Scikit-Learn (Random Forest Regressor).

## 📊 Performance
The final model achieved the following results on the test set:
*   **RMSE:** $[$47,132.03]$
*   **R² Score:** $[0.7585]$
*  

## 📂 Project Structure
```text
├── data/               # Dataset files
├── models/             # Saved .pkl files (Model & Scaler)
├── notebooks/          # Google Colab notebooks
├── eda_report.html     # Interactive EDA report


├── app.py              # Streamlit application code
├── eda_report.html     # Interactive EDA report
└── submission.csv      # Final predictions
