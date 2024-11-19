# Dominant Cyclic Period Analysis in Market Data Using FFT

This repository contains a detailed analysis of cyclic patterns in market data using **Fast Fourier Transform (FFT)** methods. The project identifies both known and hidden periodic cycles in time series data, demonstrating applications in financial market analysis, forecasting, and machine learning.

## Overview

The notebook explores the following:
- Decomposition of time series data to uncover cyclic behavior.
- Identification of known cycles (daily, weekly) and hidden patterns.
- Preprocessing techniques such as smoothing, detrending, and log transformations.
- Visualization of results with interactive widgets for dynamic exploration.

This analysis is applied to BTC/USD market data but can be generalized to any trending dataset. By discovering cycles, this approach enhances trading strategies, builds predictive features for machine learning models, and reveals hidden patterns in data.

## Notebooks

Explore the project in two formats:
- **[Google Colab Notebook](https://colab.research.google.com/drive/1uceczJlT-uT6qZnrRkLwd7EdczqUQ_dH)**: Interactive environment with execution capabilities.
- **[Kaggle Notebook](https://www.kaggle.com/code/imranbukhari/btcusd-cyclic-period-analysis-with-fft)**: Hosted on Kaggle for exploration and sharing.

## Key Features

- **Interactive Analysis**: Dynamic session with adjustable parameters to fine-tune analysis.
- **Cross-Timeframe Validation**: Analyzes 1-minute, 1-hour, and 1-day data to ensure robustness.
- **Detailed Visualizations**: Frequency spectra, dominant periods, and trends.
- **Mathematical Rigor**: Noise reduction and harmonic grouping ensure reliability of results.

## Installation

To run the notebook locally, ensure the following libraries are installed:
- `numpy`
- `pandas`
- `matplotlib`
- `scipy`
- `ipywidgets`

Install dependencies via pip:
```bash
pip install -r requirements.txt
```
