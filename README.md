# Smart-City-Intelligence-Hub
Collects and fuses city sensor data (traffic sensors, weather, air quality, events) and builds models to predict near-future traffic volume for road segments. The hub also provides visual diagnostics and feature importance so city planners and operators can act on predictions.

# Smart City Intelligence Hub

**Smart City Intelligence Hub** is an industry-oriented data science project that demonstrates end-to-end forecasting of traffic volume using multi-source urban sensor data. It includes data generation, feature engineering, model training, evaluation, and visualization. The code is written in Python using pandas, scikit-learn, and matplotlib.

## Features
- Synthetic dataset generator that simulates traffic, weather, air quality and event effects
- Feature engineering: cyclical time features, lag features, rolling means
- Train/test split preserving time order
- Random Forest regression with hyperparameter tuning
- Evaluation using RMSE and R² and visualization of Actual vs Predicted
- Modular code for easy extension to other tasks (energy forecasting, AQI predictions)

## Repo structure
