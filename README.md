# Cryptocurrency Data Analysis and Prediction Project

This project retrieves, analyzes, and predicts cryptocurrency trading data. Using historical data, it calculates metrics and applies a machine learning model to forecast future price changes.

## Project Structure

- **data_fetcher.py**: Fetches historical data from CryptoCompare.
- **metric_calculator.py**: Calculates metrics (highs, lows, percentage differences).
- **ml_model.py**: Trains a model to predict price changes.
- **main.py**: Runs the entire workflow, saving data to an Excel file.

## Setup

1. **API Key**: Get a CryptoCompare API key and add it to `data_fetcher.py`.

2. **Install Requirements**:
   ```bash
   pip install pandas requests scikit-learn openpyxl
## Running the Project

To execute the project, run the following command in your terminal:

```bash
python main.py
