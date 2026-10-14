# Household Electricity Consumption Prediction

## Project Overview
This project predicts household electricity consumption using
an LSTM (Long Short-Term Memory) neural network.

## Objectives
- Load and preprocess electricity consumption data.
- Handle missing values and normalize numerical data.
- Generate sequences from historical measurements.
- Train an LSTM model to predict future consumption.
- Evaluate the model using MAE and RMSE.
- Visualize actual and predicted electricity consumption.

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- TensorFlow / Keras

## Methodology
1. Load the household electricity dataset.
2. Handle missing values.
3. Normalize the data.
4. Generate sequences using the previous 60 measurements.
5. Train an LSTM model.
6. Evaluate predictions using MAE and RMSE.
7. Plot actual versus predicted consumption.

## Model Evaluation
- MAE: 0.4437 kW
- RMSE: 0.6639 kW

## Example Prediction
Predicted next-minute electricity consumption: 4.2995 kW

## Dataset
The project uses the Household Electric Power Consumption dataset.

## Execution
Open the Jupyter Notebook in Google Colab and run the cells
in the correct order.
