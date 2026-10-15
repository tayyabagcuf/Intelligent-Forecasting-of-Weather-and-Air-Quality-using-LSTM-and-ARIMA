# Forecasting Analysis Using ARIMA and LSTM Models

Author: Tayyaba

## Project Highlight

This project presents an intelligent environmental forecasting system that combines IoT-based data acquisition with advanced time-series prediction models. The system monitors weather-related parameters and uses both LSTM and ARIMA models to forecast future temperature and air quality trends.

The design is practical, scalable, and relevant to real-world applications in smart cities, agriculture, climate monitoring, and public health support.

## Why This Project Matters

Environmental conditions are highly dynamic and strongly influenced by past observations. Accurate forecasting can help in:

- early weather awareness
- air quality monitoring
- agricultural planning
- smart infrastructure decision-making
- public health risk reduction

This project addresses that need by building a forecasting pipeline that turns raw sensor data into actionable predictive insights.

## Objectives

- Design a weather monitoring prototype using IoT components.
- Collect and preprocess environmental data.
- Apply ARIMA and LSTM models for forecasting.
- Analyze and compare the predictive performance of both models.
- Demonstrate the usefulness of machine learning in environmental prediction.

## System Overview

The project follows an end-to-end data flow:

1. Sensor data acquisition from environmental hardware.
2. Data cleaning and preprocessing.
3. Time-series transformation for forecasting.
4. Model training and evaluation.
5. Visualization of predicted outcomes.
6. Comparison of forecasting effectiveness.

## Hardware and Data Collection

The prototype integrates NodeMCU with sensors such as DHT11 and BMP180 to monitor temperature, humidity, and pressure. The data is transmitted to a cloud platform for storage and analysis, creating a real-time monitoring environment.

This combination of hardware and analytics makes the project more than a theoretical model—it reflects a realistic smart-monitoring system.

## Forecasting Models

### LSTM Model

LSTM is a deep learning model designed for sequential data. It captures long-term dependencies and nonlinear patterns, making it highly effective for forecasting environmental variables where historical trends strongly influence future behavior.

### ARIMA Model

ARIMA is a statistical forecasting approach used for time-series analysis. It is effective for structured temporal patterns and acts as a strong baseline for comparing predictive accuracy with the LSTM model.

## Experimental Results

### Temperature Forecasting

![Temperature Forecast Comparison](assets/notebook-output/Weather_Forecast_Parameter-Temperature-cell48-output0.png)

The temperature forecast demonstrates how the model follows the observed trend and captures short- and long-term variations in the data. The LSTM-based approach is particularly effective in learning nonlinear dependencies in the time series.

### AQI Forecasting using LSTM

![AQI Forecast Comparison](assets/notebook-output/rnn-lstm-model-AQI-forecasting-cell46-output1.png)

This plot highlights the LSTM model’s ability to track AQI changes over time and model the dynamic pattern of pollution-related data.

### AQI Forecasting using SARIMAX

![SARIMAX AQI Forecast](assets/notebook-output/sarima-model-AQI-forecasting-cell22-output1.png)

The SARIMAX model provides a classical time-series benchmark and helps evaluate whether the deep learning model delivers meaningful improvements in predictive quality.

## Key Findings

- LSTM performs strongly on nonlinear and sequential environmental data.
- ARIMA remains useful as a statistical benchmark and a simpler forecasting baseline.
- The combination of sensing and prediction supports practical monitoring applications.
- The system shows strong potential for smart environmental decision-making.

## Impact and Significance

This project demonstrates how machine learning can improve traditional environmental monitoring by adding predictive intelligence. Instead of only observing current conditions, the system can anticipate future behavior and support more informed planning.

This makes the project valuable for both academic evaluation and real-world applications in sustainable monitoring systems.

## Conclusion

The project successfully integrates IoT hardware, data analytics, and forecasting models into a unified environmental prediction system. The results confirm that LSTM-based forecasting is highly effective for complex weather and AQI patterns, while ARIMA remains a meaningful comparison model.

Overall, the project is a strong semester-level research and development effort that combines practical engineering with meaningful data science.

## Author

Tayyaba

---
