# Stock Market Analysis and Prediction

## Overview
This project is an exploratory data analysis (EDA) and machine learning study focused on analyzing the historical performance of major technology stocks (Apple, Google, Microsoft, and Amazon). The project utilizes data visualization to understand past trends and implements a Long Short-Term Memory (LSTM) neural network to predict future stock closing prices.

## Key Questions Explored
The analysis addresses several core financial questions:
1. **Historical Changes:** What was the change in price of the stock over time?
2. **Moving Averages:** What was the moving average of the various stocks (10, 20, and 50 days)?
3. **Daily Returns:** What was the daily return of the stock on average?
4. **Stock Correlations:** What was the correlation between different stocks' closing prices and daily returns?
5. **Risk Analysis:** How much value do we put at risk by investing in a particular stock?
6. **Price Prediction:** How can we attempt to predict future stock behavior using Deep Learning?

## Machine Learning Integration
In addition to baseline statistical analysis, the project aims to predict the future closing price of Apple Inc. (AAPL). 
- **Model:** A multi-layered Long Short-Term Memory (LSTM) Recurrent Neural Network (RNN).
- **Data Scaling:** MinMaxScaler from `scikit-learn` is used to scale closing prices between 0 and 1.
- **Evaluation:** The model determines the Root Mean Squared Error (RMSE) to validate the effectiveness of its predictions against a testing dataset.

## Technologies Used
- **Python Data Stack:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Financial Data Retrieval:** yfinance, pandas-datareader
- **Machine Learning:** Scikit-learn (MinMaxScaler), Keras/TensorFlow (Sequential, Dense, LSTM)

## Getting Started

### Prerequisites
Make sure you have Python installed. You can install all the required libraries using pip:
```bash
pip install pandas numpy matplotlib seaborn yfinance pandas-datareader scikit-learn keras tensorflow
```

### Running the Project
You can explore the analysis by running either the Jupyter Notebook or the provided Python script:
- **Jupyter Notebook:** Open `Stock Market Analysis.ipynb` in Jupyter and run the cells sequentially to see the generated interactive visualizations and training steps.
- **Python Script:** Execute `Stock Market Analysis.py` to run the analysis natively.

## References
- Inspired by the [Learning Python for Data Analysis and Visualization](https://www.udemy.com/course/learning-python-for-data-analysis-and-visualization/) course by Jose Portilla on Udemy.
