# Account-Takeover-Prediction

This repository contains a machine learning project aimed at identifying and predicting account takeovers on the Amazon marketplace. The goal is to develop a model that can detect suspicious behavior and alert the team to take proactive measures to prevent fraud, protecting customers and Amazon sellers.

## Table of Contents
1. Introduction
2. Project Structure
3. Dataset
4. Installation
5. Usage
6. Model Performance
7. Contributing
8. License
9. Introduction
    
* Account takeovers are a significant threat to online marketplaces like Amazon. This project leverages machine learning 
  techniques to identify and predict suspicious activities indicative of account takeovers.

# Dataset
The dataset used for training the model includes features such as:

* User ID
* Transaction ID
* Amount
* Transaction Date
* Login Frequency
* IP Address
* Device Info
* Transaction Count
* Account Age
* Previous Flags
* Target (0 for normal, 1 for suspicious)
  
## Installation

## Clone the repository:
`git` clone https://github.com/diyabodiwala/Account-Takeover-Prediction.git

## Navigate to the project directory:
`cd` Account-Takeover-Prediction/models

## Install the required dependencies:
`pip` install -r requirements.txt

## Usage
* Data Exploration: Use data_exploration.ipynb to explore the raw data.
* Feature Engineering: Use feature_engineering.ipynb to process and create new features.
* Model Training: Use model_training.ipynb to train the model.
* Evaluation: Use evaluation.ipynb to evaluate the model performance.

## Model Performance

The model was evaluated using various performance metrics:

Accuracy: 92%,
Precision: 90%,
Recall: 85%,
F1-Score: 87%

The confusion matrix is as follows:

True Positives (TP): 35,
False Positives (FP): 3,
False Negatives (FN): 5,
True Negatives (TN): 57
For detailed performance metrics, refer to the model_performance_report.pdf in the reports directory.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

