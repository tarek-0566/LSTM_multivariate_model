# LSTM_multivariate_model
A multivariate LSTM model
This repository contains code for an LSTM (Long Short-Term Memory) model used for time series prediction. The model is trained to predict the Qdot_Storage_out values based on historical data.

## Dependencies

- pandas
- matplotlib
- scikit-learn
- tensorflow
- keras

## Data

The code uses two CSV files as input data:
- `avg_year_resampled - Copy.csv`: This file contains data used for training the model.
- `extreme_summer - Copy.csv`: This file contains data used for testing the model.

## Usage

To use the code, follow these steps:

1. Install the required dependencies using pip:
2. Clone the repository and navigate to the project directory:
3. Run the Python script:

## Model Architecture

The LSTM model architecture used for this project is as follows:

- Layer 1: LSTM with 128 units, LeakyReLU activation, and L2 regularization
- Layer 2: LSTM with 64 units, LeakyReLU activation, and L2 regularization
- Layer 3: Dropout layer with a rate of 0.3
- Layer 4: LSTM with 64 units, LeakyReLU activation, and L2 regularization
- Layer 5: Dropout layer with a rate of 0.3
- Layer 6: LSTM with 64 units, LeakyReLU activation, and L2 regularization
- Layer 7: Dropout layer with a rate of 0.3
- Layer 8: LSTM with 64 units and LeakyReLU activation
- Layer 9: Dropout layer with a rate of 0.3
- Output Layer: Dense layer with 1 unit (Regression task)

## Results

The model's performance was evaluated using the mean absolute percentage error (MAPE) and Root Mean Squared Error (RMSE) metrics. The results obtained results are as follows:

- MAPE: [Value]
- RMSE: [Value]

## Visualizations

![Actual vs. Predicted]

## Contact

For any questions or feedback, please contact Md.Tarekul Islam (mailto: tarek111405iut@gmail.com).

