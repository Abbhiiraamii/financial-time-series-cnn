# Financial Time Series Forecasting using CNN

This project explores how signal processing and deep learning can be combined to analyze financial time series data and predict stock prices.

### Name:ABHIRAMI S  
### Reg no:TCR24CS003  

## Overview

Financial data such as stock prices can be treated as signals that change over time.
In this project, the time-domain stock price signal is transformed into a time–frequency representation using Short-Time Fourier Transform (STFT). The resulting spectrogram is then used as input to a Convolutional Neural Network (CNN) for prediction.

## Pipeline

Stock Price Data → STFT → Spectrogram → CNN Model → Price Prediction

## Data Source

Stock market data was obtained from Yahoo Finance for the following companies:

* Reliance Industries
* Tata Consultancy Services (TCS)
* Infosys

## Methods Used

* Time series visualization
* Fourier Transform for frequency analysis
* Spectrogram generation using STFT
* Convolutional Neural Network (CNN) for prediction
* Mean Squared Error (MSE) for evaluation

## Technologies

* Python
* Google Colab
* TensorFlow / Keras
* NumPy
* SciPy
* Matplotlib
* yfinance

## Results

The project demonstrates how financial time series can be converted into spectrogram representations and analyzed using CNN-based models. Due to the limited dataset used in this experiment, prediction accuracy is limited, but the pipeline successfully illustrates the methodology.

## Repository Contents

* `stock_price_prediction_stft_cnn.ipynb` – Main notebook containing the full implementation and results.
