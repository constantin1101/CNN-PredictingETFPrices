# CNN-PredictingETFPrices

Welcome to the ETF Price Trend Prediction Project! This repository is dedicated to forecasting ETF price trends using convolutional neural networks (CNNs) and advanced data visualization techniques. 


# Project Overview

ETFs are a crucial component of modern financial markets, offering a blend of diversification and liquidity. Predicting their price trends, however, poses unique challenges due to their complex nature and the influence of a wide range of market factors. Our project addresses these challenges by employing a novel methodology that transforms traditional financial time series data into various image formats, enabling CNNs to extract and learn intricate patterns and correlations.


# Key Features

Advanced Visualization Techniques: Incorporating monochrome and colorful price analysis, metric-based line charts, and algorithmic pattern identification for comprehensive market insights.
Deep Learning Models: Utilizing CNNs to analyze these visualizations, our models adeptly interpret and predict ETF price trends.
Robust Data Preprocessing and Structured Training: Detailed preprocessing of financial data and structured model training to effectively harness CNN capabilities.
Comprehensive Dataset and Evaluation: Employing a rich dataset and rigorous evaluation metrics to ensure robust model performance.


# Repository Structure

data/: Datasets of historic ETFs.
models/: Trained models.
evaluation/: Preformance metrics and trading results.
images/: Created images of different types.
labels/: Labels with imagespath and additional information.
baseline/: Buy-and-hold baseline returns.


# Key Notebooks

build_chart_images.ipynb: Builds financial images from ETF data. Configurable constants for testing and transfer learning scenarios.
train_models.ipynb: Processes training data images and trains models on various timeframes and prediction windows.
evaluate_model.ipynb: Processes images for testing and transfer, evaluates models, performs trading strategies, and overlays images for insights. Outputs are saved in /evaluation.


# Getting Started

Clone the repository.
Ensure you have Jupyter Notebooks installed. 
Ensure all dependencies listed in requirements.txt are installed.


# Contribution and Support

We welcome contributions! For suggestions, bug reports, or feature requests, please open an issue. Contact us at constantin.e99@web.de for further assistance.