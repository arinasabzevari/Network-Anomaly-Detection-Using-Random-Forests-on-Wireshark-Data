
# Network Anomaly Detection Using Random Forests on Wireshark Data

A machine learning project that detects anomalous network traffic using a Random Forest classifier trained on features extracted from Wireshark packet captures.

## Overview

This notebook processes network traffic data (captured via Wireshark) and trains a Random Forest model to distinguish normal traffic from anomalous/suspicious activity. Results are visualized using bar plots, probability histograms, and an anomaly scatter plot, producing interpretable, stable anomaly detection suitable for monitoring or post-capture network behavior analysis.

## Contents

- `final_project_comp432.ipynb` — main notebook containing data preprocessing, model training, evaluation, and visualizations

## Requirements

- Python 3.x
- Jupyter Notebook / JupyterLab (or Google Colab)
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Usage

1. Open `final_project_comp432.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab.
2. Run the cells in order to preprocess the data, train the Random Forest model, and generate the evaluation plots.

## Method

Network traffic features are extracted from Wireshark capture data and used to train a Random Forest classifier. Model performance and anomaly patterns are visualized through bar plots, probability histograms, and an anomaly scatter plot.
