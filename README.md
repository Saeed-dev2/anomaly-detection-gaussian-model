# Anomaly Detection with Multivariate Gaussian Distribution

This repository contains Python code for anomaly detection using a probabilistic machine learning approach. The algorithm models the normal behavior of data using a Multivariate Gaussian distribution and flags data points as anomalies based on a learned probability threshold.

## 🔍 Overview

- Estimate data distribution parameters (mean and variance)
- Compute probability for each data point
- Select threshold using F1-score on validation set
- Detect anomalies based on probability threshold

## 📊 Technologies Used

- Python 3
- NumPy
- SciPy
- Matplotlib
- Scikit-learn (for evaluation)

## 📈 Applications

- Fraud detection
- Network intrusion detection
- Equipment fault diagnosis
- Rare event prediction

## 📁 Structure

- `anomaly_detection.py`: Core implementation
- `utils.py`: Helper functions for visualization and data loading
- `data/`: Example datasets
- `notebooks/`: Jupyter notebooks for experimentation

## ✅ Author
Muhammad Saeed
