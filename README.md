
# Santander Customer Transaction Prediction

## Note: This code (and this README) are very much works in progress and will continuously be updated in the coming weeks!

## Project Overview

This code was created to predict customers' future purchases and transactions using consumer behavior data provided by Santander. This code serves to provide data exploration/ preprocessing and a simple multilayer perceptron (MLP) neural network in order to classify consumer behavior and make predictions. 

## Code Structure

The code for this project is organized as follows:

1. **Data Exploration**: Initial exploration of the dataset, including data summary statistics, class distribution visualization, and feature distribution analysis.

2. **Data Preprocessing**: Data preprocessing steps such as feature scaling and handling missing values are performed.

3. **Model Building**: A deep learning model is constructed using TensorFlow and Keras. The model architecture includes multiple hidden layers with dropout and regularization techniques to prevent overfitting.

4. **Hyperparameter Tuning**: Grid search is used to find the best hyperparameters for the model. This step aims to optimize the model's performance.

5. **Model Evaluation**: The model's performance is evaluated using ROC AUC score, which is a common metric for binary classification tasks.

6. **Results**: The best model's hyperparameters and ROC AUC score are displayed in the results section.
