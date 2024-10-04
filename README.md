# Deep Learning Project 
### Temperature Prediction Using Deep Learning Models

This project aims to predict future temperatures using historical weather data from the Sri Lanka Weather dataset.  We employ four advanced deep learning models—Recurrent Neural Network (RNN), Long Short-Term Memory (LSTM), Gated Recurrent Unit (GRU), and Convolutional Neural Network (CNN) to analyze and compare their performance in forecasting future temperatures. The dataset is sourced from Kaggle and includes a wide range of meteorological parameters from 2010 to June 2024, covering all districts of Sri Lanka.

### Dataset

- **Name**: Sri Lanka Weather Dataset
- **Source**: [Kaggle](https://www.kaggle.com/datasets/tharindumadhusanka9/sri-lanka-weather-data-for-all-districts)
- **Time Period**: 2010 to June 2024
- **Features**:
  - **Date** (YYYY-MM-DD)
  - **District**
  - **Maximum Temperature** (°C)
  - **Minimum Temperature** (°C)
  - **Precipitation** (mm)
  - **Humidity** (%)
  - **Wind Speed** (km/h)
  - etc.. 
- **Description**: The dataset contains daily weather observations from all districts in Sri Lanka. It includes essential features such as temperature, humidity, precipitation, wind speed, and more, which are used to build predictive models for future temperature forecasting.

## Project Objectives:
1. To predict future temperatures based on historical weather data from Sri Lanka.
2. To compare the performance of four deep learning models:
   - **Recurrent Neural Network (RNN)**
   - **Long Short-Term Memory (LSTM)**
   - **Gated Recurrent Unit (GRU)**
   - **Convolutional Neural Network (CNN)**
3. To analyze the efficiency and accuracy of each model and determine the most effective approach for temperature prediction.
4. To explore how weather features such as humidity, wind speed, and precipitation influence temperature forecasting.

## Models Used:

1. **Recurrent Neural Network (RNN):**

   - A deep learning model that works well with sequential data by passing information from one step to the next, making it useful for time series predictions like weather forecasting.

2. **Long Short-Term Memory (LSTM):**

   - An advanced type of RNN that handles long-term dependencies in sequential data. LSTM networks are effective at learning and remembering patterns over extended periods, making them ideal for time-series predictions.

3.**Gated Recurrent Unit (GRU):**

  - A simplified version of LSTM that also captures long-term dependencies in sequential data but with fewer parameters, offering a more efficient alternative to LSTM with comparable performance.

4. **Convolutional Neural Network (CNN):**

   - Although primarily used for image data, CNNs can be adapted to capture spatial hierarchies in sequential data such as weather, focusing on localized features.



### Dependencies
- Python 3.x
- NumPy
- Pandas
- TensorFlow 
- Keras
- Matplotlib
- Seaborn

### Evaluation Metrics
- **Mean Squared Error (MSE):** Measures the average squared difference between actual and predicted values.
- **Root Mean Squared Error (RMSE):** The square root of MSE, providing the error in the original unit (°C).
- **R-squared (R²):** Indicates how well the model fits the data; values closer to 1 indicate better fit.


## Contribution
- **Jayathilaka A G K D** (GRU)
- **Rathnayake R M U V** (LSTM)
- **Gunasekara W M A S** (RNN)
- **Liyanage U S P** (CNN)


## Acknowledgments
- The dataset is provided by Tharindu Madhusanka on Kaggle.
[Sri Lanka Weather Dataset on Kaggle](https://www.kaggle.com/datasets/tharindumadhusanka9/sri-lanka-weather-data-for-all-districts)
- Special thanks to the Kaggle and open-meteo.com teams for making the data publicly available.
