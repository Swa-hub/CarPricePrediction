# CarPricePrediction
> Introduction
This project aims to predict the prices of used cars based on various features using deep learning techniques. By leveraging data preprocessing, feature engineering, and a neural network model, we aim to provide accurate price predictions.

> Table of Contents
1.Introduction
2.Dataset
3.Data Preprocessing
4.Model Architecture
5.Training
6.Evaluation
7.Results
8.Visualization
8.How to Use

> Dataset
You can find the dataset in Kaggle

> Data Preprocessing
1.Converted dataset into tensors so as to use in deep neural layers.
2.Expanded the dimensions of dataset to be used for training and testing
3.Feature Scaling: Applied normalization to scale numerical features.


> Model Architecture
The model used in this project is a neural network built with the following layers:
1.Input Layer
2.Dense Layers with ReLU activation
3.Output Layer

> Training
1.Loss Function: Mean Absolute Error (MAE)
2.Optimizer: Adam
3.Epochs: 100
4.Batch Size: 32
5.Verbose: 1
6.Learning rate: 0.1

> Evaluation
1.Metrics: Root Mean Squared Error (RMSE)
2.Validation Split: Used an 80-10-10 split for training , testing and validation data

>Results
The model achieved a Root Mean Squared Error of X on the validation set.

>Visualization:
Performed visualization and viewed actual vs predicted values in the form of bars

