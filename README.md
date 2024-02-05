# Time-Series-Forcasting-analysis
Multivariate Time Series Forecasting: Temperature and Pressure Prediction 

Introduction: 

Embark on a comprehensive exploration of multivariate time series forecasting, predicting both temperature and pressure using advanced machine learning models.

Leveraging a dataset that combines weather variables, this project involves data preprocessing, feature engineering, model creation, and evaluation.

Technologies Used: - Pandas, NumPy: Data manipulation and numerical operations - Matplotlib: Data visualization - TensorFlow, Keras: Machine learning model development - ModelCheckpoint: Model saving during training - Mean Squared Error (MSE), Adam Optimizer:Loss function and optimization - Root Mean Squared Error (RMSE): Evaluation metric

 
 Key Project Steps: 
 
 1. Univariate Time Series Forecasting (Temperature):
- Extracted hourly temperature data, creating a univariate time series.
- Implemented LSTM model architecture for temperature prediction.
- Trained and evaluated the model, visualizing predictions on training, validation, and test datasets.

 2. Multivariate Time Series Forecasting (Temperature and Pressure):
- Combined temperature and pressure datasets.
- Engineered input features and output labels for LSTM model.
- Standardized data for consistent model training.
- Developed a multivariate LSTM model predicting both temperature and pressure.
- Trained the model, validated on a separate dataset, and saved the best-performing model.

 3. Post-Processing and Visualization:
 - Post-processed model predictions to obtain meaningful temperature and pressure values.
- Visualized post-processed predictions against actual values for evaluation.
 - Plotted subsets of temperature and pressure predictions alongside actuals.

Conclusion: 

This project showcases the power of multivariate time series forecasting, accurately predicting temperature and pressure patterns. The utilization of advanced machine learning models, thorough data preprocessing, and insightful post-processing techniques contribute to the success of the predictive analytics. 
