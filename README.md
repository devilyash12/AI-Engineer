# Electricity Load Forecasting Using Machine Learning and Time Series Models

## Overview

This project focuses on electricity load forecasting using various machine learning and time series models. The models employed range from traditional time series models like ARIMA to advanced deep learning models like LSTM and Chronos. The goal is to accurately predict future electricity consumption based on historical data. The project applies feature engineering techniques to improve model performance and evaluates the models using standard metrics like Mean Squared Error (MSE), Mean Absolute Error (MAE), and R² Score.

### Key Models Used:
- **Linear Regression**
- **ARIMA**
- **Prophet**
- **LSTM (Long Short-Term Memory)**
- **Chronos** (Deep Learning)

### Key Features:
- Feature engineering including rolling averages, lag features, and percentage changes.
- Models designed to capture seasonal trends and non-linear patterns in electricity consumption.
- Evaluation metrics used to compare model performances.

---

## Getting Started

### Prerequisites

To run this project, you'll need the following installed on your system:

- Python 3.x
- Jupyter Notebook
- Required Python packages (listed in the `requirements.txt` file)

To install the necessary Python packages, run:

```bash
pip install -r requirements.txt
``` 
## Dataset
The dataset used for this project is the ETT.csv file containing electricity consumption data. Ensure that this file is in the project directory.

# How to Run
Clone the Repository

Clone this repository to your local machine using:

```bash
Copy code
git clone https://github.com/your-repository-link.git
```
Navigate to the Project Directory

```bash
Copy code
cd your-project-directory
```
Open Jupyter Notebook

Launch Jupyter Notebook in the project directory by running:

```bash
Copy code
jupyter notebook
```
Run the Program

Open the AI_Engineer.ipynb notebook and run all cells sequentially to execute the data preprocessing, model training, and evaluation steps.

You can modify the code to test other models, tune hyperparameters, or include additional features.

## Instructions for Use
### Data Preprocessing:

Load the dataset and preprocess the date column.
Check for missing values and handle them appropriately.
### Exploratory Data Analysis (EDA):

Visualize electricity consumption trends over time.
Identify seasonal patterns, weekly, and daily trends in the dataset.
### Model Training:

Each model (Linear Regression, ARIMA, Prophet, LSTM, and Chronos) is trained on the historical data.
Feature engineering is applied to improve model performance, including the use of rolling averages and lag features.
### Model Evaluation:

The models are evaluated using MSE, MAE, and R² Score.
The results of each model are plotted and compared for better insights.
## Model Overview
Linear Regression
A baseline model used to capture basic trends in the data.

### ARIMA
A traditional time-series model capturing linear trends but struggling with non-stationary data.

### Prophet
Capable of handling missing data and capturing seasonality with minimal tuning.

### LSTM
A deep learning model designed to capture both short-term and long-term dependencies in time-series data.

### Chronos
An advanced deep learning model specialized for complex time-series forecasting and non-linear patterns.

## Future Enhancements
Implement ensemble models to further improve forecasting accuracy.
Incorporate external factors (e.g., weather data, holiday schedules) to enhance model predictions.
Explore other time-series forecasting models for more robust performance.
Contributing
Feel free to submit issues or pull requests to improve the project. Contributions are always welcome!

## Contributing
Feel free to submit issues or pull requests to improve the project. Contributions are always welcome!