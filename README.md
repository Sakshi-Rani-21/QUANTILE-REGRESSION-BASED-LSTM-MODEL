# QUANTILE-REGRESSION-BASED-LSTM-MODEL
Quantile Regression based Long-Short Term Memory Model
## Project Overview
With a six-year (2019--2024) dataset of AQI values from four metropolitan cities Delhi, Mumbai, Bengaluru, and Kolkata, the project compares the models under a rolling window setup. The major processes are data preprocessing, model training, hyperparameter tuning, and performance evaluation using statistical tests like Dynamic Quantile (DQ) and Unconditional Calibration (UC).

## Key Features
- **Data Collection:** AQI data was retrieved from the official website of the Central Pollution Control Board and meteorological data was collected from vissula crossing website.
- **Data Cleaning and Preparation:** The dataset has been cleaned and pre-processed to ensure accuracy and reliability of the analysis.
- **Feature Selection:** In order to determine the most significant input variables for the prediction of AQI, a correlation-based feature selection was utilized. This method estimates the statistical correlation between the target variable (AQI) and each input feature (e.g., pollutant concentrations), and it is thus possible to choose features with a strong linear correlation with AQI 
- **Exploratory Data Analysis:** Exploratory Data Analysis (EDA) was carried out to gain an initial understanding of the data distribution, identify patterns, detect anomalies, and examine relationships between variables. Visual tools such as time series plots are employed to study the seasonal trends and variability of air pollutants and meteorological features across different cities. The distribution of AQI values was also analyzed to assess the severity of pollution over time.
- **Implimentation Environment:** Both Quantile Regression (QR) and Quantile Regression LSTM (QR-LSTM) models were executed in PyTorch and run on Google Colab. The QR model was executed with CPU capabilities, while the QR-LSTM model utilized GPU acceleration provided by the Colab environment.
## Dataset
- To access the dataset open [AQI AND WEATHER DATA_DELHI](https://github.com/Sakshi-Rani-21/QUANTILE-REGRESSION-BASED-LSTM-MODEL/blob/main/DELHI%20FINAL%20(1).xlsx)
- To access the dataset open [AQI AND WEATHER DATA_MUMBAI](https://github.com/Sakshi-Rani-21/QUANTILE-REGRESSION-BASED-LSTM-MODEL/blob/main/MUMBAI%20FINAL%20(1).xlsx)
- To access the dataset open [AQI AND WEATHER DATA_KOLKATA](https://github.com/Sakshi-Rani-21/QUANTILE-REGRESSION-BASED-LSTM-MODEL/blob/main/KOLKATA%20FINAL%20(1).xlsx)
- To access the dataset open [AQI AND WEATHER DATA_BENGALURU](https://github.com/Sakshi-Rani-21/QUANTILE-REGRESSION-BASED-LSTM-MODEL/blob/main/BENGALURU%20FINAL%20(1).xlsx)
## Model Setup
For the Quantile Regression Long Short-Term Memory (QRLSTM) model, air quality observations from four major cities Delhi, Mumbai, Kolkata, and Bengaluru were utilized, over a six-year period from 2019 to 2024. A rolling window strategy with a window of six months was used to effectively capture local temporal dependencies and changes in AQI levels.

The QRLSTM model was trained on three years of past AQI data and validated on the following six-months period. This training methodology allows the model to understand seasonal and semi-annual patterns while taking advantage of LSTM's ability to model sequential data, hence improving the accuracy and robustness of quantile-based AQI predictions in different urban settings.

## Getting Started
1. Clone this repository to your local machine.
2. Open [Google Colab Or Python script]()for the python code


