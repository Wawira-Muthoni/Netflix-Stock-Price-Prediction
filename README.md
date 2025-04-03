# Netflix Stock Price Prediction

This project aims to predict Netflix stock prices using time series analysis. It utilizes historical stock data to train 
machine learning models and forecast future price movements.

## Dataset

The dataset used for this project is `Netflix Inc. (NFLX) Stock Price 2002-2025.csv`. It contains historical Netflix stock price data, including:

* Date
* Open
* High
* Low
* Close
* Volume

## Methodology

The project employs time series analysis techniques to predict stock prices. Key steps include:

1.  **Data Acquisition and Preprocessing:**
    * Loading historical stock data.
    * Handling missing values and outliers.
    * Feature engineering (lagged features).
    * Data scaling.
    * Splitting the data into training, validation, and test sets.
2.  **Model Selection and Training:**
    * LSTM (Long Short-Term Memory) neural network.
    * XGBoost (Extreme Gradient Boosting).
    * Ensemble models (Averaging).
    * Stacking models.
3.  **Model Evaluation:**
    * Root Mean Squared Error (RMSE).
    * SHAP (SHapley Additive exPlanations) values for feature importance.
    * Visualizations of actual vs. predicted prices.

## Results

* The XGBoost model demonstrated superior performance compared to the LSTM model.
* Feature importance analysis using SHAP values highlighted the significance of lagged open and close prices.
* The project encountered challenges related to LSTM model configuration and data scaling.

## Requirements

* Python 3.x
* Libraries:
    * pandas
    * numpy
    * scikit-learn
    * tensorflow/keras
    * xgboost
    * shap
    * matplotlib
    * seaborn

## Installation

1.  Clone the repository:

    ```bash
    git clone [repository_url]
    ```

2.  Install the required libraries:

    ```bash
    pip install pandas numpy scikit-learn tensorflow xgboost shap matplotlib seaborn
    ```

3.  Run the Jupyter Notebook `Netflix__Stock__Price.ipynb` to execute the code.




