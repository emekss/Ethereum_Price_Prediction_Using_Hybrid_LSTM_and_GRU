 # Ethereum Price Prediction System using Hybridized LSTM and GRU Model
This repository contains the implementation of a price prediction system for Ethereum using a hybridized LSTM and GRU model. The system aims to forecast Ethereum's price fluctuations, leveraging the strengths of both LSTM and GRU architectures.

## Table of Contents
- [Introduction](#introduction)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Evaluation Metrics](#evaluation-metrics)
- [Results](#results)
- [Contributions](#contributions)
- [License](#license)

## Introduction
Cryptocurrency price prediction is a challenging task due to market volatility. This project focuses on developing a robust Ethereum price prediction system that combines LSTM and GRU models to capture both short-term and long-term dependencies in the price data.

## Requirements
- Python 3.x
- TensorFlow
- Pandas
- NumPy

## Installation
1. Clone this repository: `git clone https://github.com/emekss/ethereum-price-prediction.git`
2. Navigate to the project directory: `cd ethereum-price-prediction`
3. Install the required packages: `pip install -r requirements.txt`

## Usage
1. Prepare your Ethereum price dataset (CSV format recommended).
2. Update the dataset path and hyperparameters in the relevant scripts.
3. Train the LSTM-GRU model: `python train.py`
4. Evaluate the model's performance: `python evaluate.py`
5. Make predictions using the trained model: `python predict.py`

## Dataset
The Ethereum price dataset was obtained from Yahoo Finance (link: https://finance.yahoo.com). It includes daily price data, open price, close price, high and low prices, and trading volume.

## Model Architecture
The hybridized LSTM and GRU model combines the strengths of both architectures to capture both long-term and short-term dependencies in the Ethereum price data.

## Evaluation Metrics
The model's performance is assessed using common evaluation metrics: R2 Score, Root Mean Squared Error (RMSE), Mean Squared Error (MSE), Mean Absolute Error (MAE), and Explained Variance Score (EVS)

## Results
The LSTM-GRU model showed the best real-time prediction capabilities, demonstrating the effectiveness of the hybrid approach. Despite its computational cost, the model's accuracy and performance make it a promising choice for Ethereum price prediction.

## Contributions
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
