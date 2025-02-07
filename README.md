# Bitcoin Pi Cycle Top Indicator Predictor

## Overview
This project uses machine learning (LSTM) to predict future values of the Bitcoin Pi Cycle Top Indicator. The Pi Cycle Top Indicator is a popular technical analysis tool used to identify potential market cycle tops in Bitcoin.

## Features
- Historical data analysis of the Pi Cycle Top Indicator
- LSTM-based machine learning model for prediction
- Future predictions up to 2030
- Visualization of historical, test, and future predictions
- Time series analysis with proper handling of dates and timezones

## Technical Details
- **Model**: Long Short-Term Memory (LSTM) neural network
- **Data Processing**: 
  - Time series scaling
  - Sequence generation
  - UTC timezone handling
- **Visualization**: Matplotlib-based plots showing:
  - Historical data
  - Test predictions
  - Future predictions
  - Present day marker

## Requirements
python
pandas
numpy
tensorflow
keras
matplotlib

## Usage
1. Load historical Pi Cycle Top Indicator data
2. Train the LSTM model on the historical data
3. Generate predictions for future dates
4. Visualize results with combined historical and predicted data

## Results
The model provides predictions for the Pi Cycle Top Indicator up to December 31, 2030, with:
- Historical data in blue
- Test predictions in green
- Future predictions in red (dashed line)
- Present day marked with a vertical line

## Disclaimer
This project is for educational purposes only. The predictions should not be used as financial advice. Always do your own research when making investment decisions.

## License
[Add your chosen license here]

## Test section
This is a test section.
