# QUANTILE-REGRESSION-BASED-LSTM-MODEL
Quantile Regression based Long-Short Term Memory Model
## Project Overview
With a six-year (2019--2024) dataset of AQI values from four metropolitan cities Delhi, Mumbai, Bengaluru, and Kolkata, the project compares the models under a rolling window setup. The major processes are data preprocessing, model training, hyperparameter tuning, and performance evaluation using statistical tests like Dynamic Quantile (DQ) and Unconditional Calibration (UC).

## Key Features
- **Data Cleaning and Preparation:** The dataset has been cleaned and pre-processed to ensure accuracy and reliability of the analysis.
- **Feature Selection:** In order to determine the most significant input variables for the prediction of AQI, a correlation-based feature selection was utilized. This method estimates the statistical correlation between the target variable (AQI) and each input feature (e.g., pollutant concentrations), and it is thus possible to choose features with a strong linear correlation with AQI 
- **Exploratory Data Analysis:** Exploratory Data Analysis (EDA) was carried out to gain an initial understanding of the data distribution, identify patterns, detect anomalies, and examine relationships between variables. Visual tools such as time series plots are employed to study the seasonal trends and variability of air pollutants and meteorological features across different cities. The distribution of AQI values was also analyzed to assess the severity of pollution over time.
- **Implimentation Environment:** Both Quantile Regression (QR) and Quantile Regression LSTM (QR-LSTM) models were executed in PyTorch and run on Google Colab. The QR model was executed with CPU capabilities, while the QR-LSTM model utilized GPU acceleration provided by the Colab environment.
## Dataset
- To access the dataset open 
