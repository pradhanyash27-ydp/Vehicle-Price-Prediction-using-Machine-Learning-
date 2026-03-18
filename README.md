# Vehicle-Price-Prediction-using-Machine-Learning-

This project develops an end-to-end machine learning pipeline for predicting vehicle prices using structured vehicle data. The model estimates the market value of a car based on attributes such as manufacturer, model, year, mileage, engine specifications, fuel type, transmission, and other vehicle features.

The workflow includes data preprocessing, feature engineering, model training, evaluation, and explainability. Key preprocessing steps include handling missing values, creating engineered features such as vehicle age and log-transformed mileage, limiting high-cardinality categorical variables, and extracting textual information using TF-IDF vectorization.

###### Multiple regression models were trained and compared:

Linear Regression (baseline model)

Random Forest Regressor

XGBoost Regressor

Model performance was evaluated using RMSE, MAE, and R² score, where XGBoost achieved the best performance, effectively capturing nonlinear relationships between vehicle attributes and price. Feature importance and SHAP analysis were used to interpret model predictions.

The trained model, preprocessing transformers, and TF-IDF vectorizer are saved using joblib, enabling the system to generate real-time price predictions for new vehicle data.

This project demonstrates how machine learning can support automated vehicle valuation systems for car marketplaces, dealerships, auction platforms, and consumer price estimation tools.
