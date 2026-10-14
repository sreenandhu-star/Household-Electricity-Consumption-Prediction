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

## Dataset

This project uses the Individual Household Electric Power Consumption dataset from the UCI Machine Learning Repository.

**Dataset Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption)

The dataset contains household electricity consumption measurements collected over time.

### Dataset Used

- File name: household_power_consumption.txt
- Data format: Semicolon-separated text file
- Prediction target: Global_active_power
- Data preprocessing: Missing values are handled before training.

### How to Use the Dataset

1. Download the dataset from the UCI Machine Learning Repository.
2. Extract the downloaded archive if necessary.
3. Upload household_power_consumption.txt to Google Colab.
4. Run the notebook using the uploaded dataset.

## Dependencies

Install the required Python libraries using:

```bash
pip install -r requirements.txt
