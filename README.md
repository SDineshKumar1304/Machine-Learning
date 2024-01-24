# Multiple Linear Regression Model 

## Overview

This repository contains a simple implementation of a linear regression model trained on a dataset to predict car prices. The model is built using the scikit-learn library in Python.
## Features

- **wheelbase:** The distance between the centers of the front and rear wheels.
- **carlength:** The length of the car.
- **carwidth:** The width of the car.
- **carheight:** The height of the car.
- **curbweight:** The weight of the car without passengers or cargo.
- **enginesize:** The size of the car's engine.
- **boreratio:** The ratio of the cylinder bore's diameter to its stroke length.
- **stroke:** The length of the piston stroke.
- **compressionratio:** The ratio of the volume of the cylinder and the combustion chamber when the piston is at the bottom of its stroke to the volume when it's at the top.
- **horsepower:** The car's engine power.

## Files and Directories

- **linear_regression_model.ipynb**: Jupyter Notebook containing the code for training the linear regression model.
- **linear_regression_model.joblib**: The saved model file using joblib.
- **new_unseen_data.csv**: A sample CSV file with new unseen data for testing the model.

## Requirements

- Python 3.x
- Required Python libraries can be installed using `pip install -r requirements.txt`.

## Model Evaluation

The model's performance is evaluated using Mean Squared Error (MSE) and R-squared metrics.

## Author

S.Dinesh Kumar

Feel free to reach out for any questions or improvements!
