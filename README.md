# JSW Steel Stock Analysis - PySpark Project

## 📋 Project Overview
This project performs a comprehensive analysis of JSW Steel stock data using PySpark to identify patterns, trends, and correlations for investment insights. The analysis covers data cleaning, exploratory data analysis, feature engineering, and trend identification.

## 👥 Team Members (Group 8 - InfoForge)
- Nikhil Sharma
- Mitanshu Ijankar
- Neha Sardar
- Mrudula Khobragadhe
- Om Salunkhe
- Nilesh Nawale

## 🎯 Project Goals
- Perform detailed analysis of JSW Steel stock data
- Identify patterns, trends, and correlations
- Provide actionable insights for investment decision-making
- Demonstrate end-to-end data processing using PySpark

## 🛠️ Technical Stack
- **PySpark**: Version 3.5.1
- **Java**: OpenJDK version 1.8.0_462
- **Dataset**: JSWSTEEL.csv (20+ years of stock data)

## 📊 Dataset Information
- **Records**: 5,336 entries
- **Time Period**: 2003-2023 (20+ years)
- **Columns**: Date, Open, High, Low, Close, Adj Close, Volume

## 🔧 Project Tasks

### Task 1: Data Loading and Cleaning
- Loaded dataset and inspected schema
- Identified minimal null values (1 each in Open, High, Low, Close, Volume)
- Renamed "Adj Close" to "Adj_Close" for consistency

### Task 2: Data Type Conversion
- Converted Date to timestamp format
- Cast numerical columns to appropriate types (double/long)
- Ensured data consistency for analysis

### Task 3: Statistical Analysis
- **Average Close Price**: ₹225.06
- **Price Range**: ₹10.39 to ₹1039.09
- **Standard Deviation**: 254.56 (indicating significant volatility)

### Task 4: Duplicate Handling
- No duplicate rows found in the dataset

### Task 5: Trend Analysis
- Identified consistent growth from ₹10 (2003) to over ₹1000
- Observed increasing trading volume indicating growing investor interest

### Task 6: Feature Engineering
- Created "Close_filled" column using forward fill for time series continuity
- Ensured data readiness for ML forecasting models

### Task 7: Daily Returns Calculation
- Calculated percentage daily returns
- Identified typical stock cycle patterns with bullish movements and corrections

### Task 8: Moving Average Indicators
- Implemented SMA-50 and SMA-200
- Observed "Golden Cross" pattern confirming bullish momentum
- SMA_50 consistently above SMA_200 indicating sustained uptrend

### Task 9: Correlation Analysis
- **Open vs Close**: +0.98 (strong correlation)
- **High vs Low**: +0.99 (very strong correlation)
- **Volume vs Close**: +0.62 (moderate positive correlation)

### Task 10: Visualization
- Closing price trends over time
- Daily returns volatility
- SMA comparisons for trend confirmation

## 📈 Key Insights

### Performance Metrics
- **Massive Growth**: Stock price increased from ₹10 to over ₹1000
- **Average Performance**: ₹225 average closing price over 20 years
- **Volatility**: Regular fluctuations with consistent recovery patterns

### Market Behavior
- **Volume-Price Correlation**: Trading activity increases with price rises
- **Bullish Trends**: Sustained upward movement confirmed by SMA analysis
- **Cyclical Patterns**: Typical bull and correction phases observed

### Data Quality
- **Clean Dataset**: No duplicates after preprocessing
- **Minimal Missing Values**: Successfully handled during cleaning
- **Structured Format**: Ready for advanced analytics and ML modeling

## 🚀 Technical Achievements
- Successfully implemented distributed data processing using PySpark
- Handled large-scale financial data efficiently
- Demonstrated end-to-end data engineering pipeline
- Applied window functions for time series analysis
- Performed comprehensive statistical and correlation analysis

## 📋 Future Scope
- Implement ML forecasting models (ARIMA, LSTM)
- Real-time stock analysis pipeline
- Comparative analysis with industry peers
- Sentiment analysis integration with news data
- Portfolio optimization recommendations


## 🏆 Conclusion
This PySpark project successfully demonstrates an end-to-end data pipeline for financial analysis, showcasing strong data engineering, analytical, and visualization skills. The analysis reveals JSW Steel's exceptional long-term growth potential and provides a solid foundation for predictive modeling and investment strategy development.
