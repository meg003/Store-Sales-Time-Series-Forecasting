Sales Prediction using Random Forest Regression

Project Description
This project implements a Random Forest Regression model to predict sales based on historical data. The model takes into account various features including temporal patterns, store information, and product families to generate accurate sales forecasts.

Features
- Advanced time-series feature engineering
- Lag feature creation (7 and 14-day lags)
- Rolling mean calculations
- Automated date feature extraction
- Standardized data preprocessing
- Model performance visualization
- Feature importance analysis

Model Performance
- R² Score: 0.968 (96.8% accuracy)
- RMSE: 196.79
- Execution Time: ~3.4 minutes

Dependencies
```python
pandas
numpy
scikit-learn
matplotlib
seaborn
