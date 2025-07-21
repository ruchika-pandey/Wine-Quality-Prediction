# Wine-Quality-Prediction
Wine quality prediction project was made by using three machine learning models: Linear Regression, XGBoost Regressor, and LightGBM Regressor. The goal was to predict wine quality based on various chemical properties.
-->Key Highlights:
Data Preprocessing: Handled categorical 'color' feature with LabelEncoder and scaled features using StandardScaler.
-->Model Evaluation:
Linear Regression: MAE: 0.564, MSE: 0.423, R²: 0.364

XGBoost Regressor: MAE: 0.418, MSE: 0.307, R²: 0.549

LightGBM Regressor: MAE: 0.396, MSE: 0.281, R²: 0.587
-->Visualization: Created scatter plots to compare actual vs. predicted quality and bar charts to showcase feature importance.
-->Insights: LightGBM outperformed other models, with 'total sulfur dioxide' and 'density' being the most influential features.
Skills: Evaluation Metrics, Hyperparameter Tuning, XGBoost, LightGBM, StandardScaler, LabelEncoder, Python, Matplotlib, Seaborn, Statistical Data Analysis
