# Quantitative Stock Forecasting & Investment Trend Analysis using ML and Markov Models

## Overview
This project focuses on forecasting short-term stock price movement and analyzing investment trends using a combination of Machine Learning models and Markov Chain-based probabilistic modeling.

The system was developed using Python and leverages 10 years of historical stock market data to study market behavior, predict directional trends, and evaluate forecasting performance using statistical metrics.

The project combines:
- Time-series forecasting
- Lag feature engineering
- Markov state transition analysis
- Machine Learning-based prediction models
- Risk and trend probability assessment

---

## Project Description
- Built a machine learning-driven forecasting pipeline using Python for analyzing 10 years of historical stock data using time-series techniques and lag feature engineering to forecast short-term price movement and directional trends.
- Developed Markov Chain-based market state transition models to evaluate bullish, bearish, and sideways trend probabilities for risk assessment.
- Implemented and benchmarked ML models including XGBoost using MAE, RMSE, and R² metrics to optimize prediction accuracy and investment decision support.

---

# Technologies Used

## Programming Language
- Python

## Libraries & Frameworks
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

## Tools
- Jupyter Notebook
- Google Colab

---

# Dataset
The project uses:
- 10 years of historical stock market data
- Daily stock prices and trading information
- Multiple publicly traded stocks across different sectors

### Features Used
- Open
- High
- Low
- Close
- Adjusted Close
- Volume

---

# Methodology

## 1. Data Preprocessing
- Handled missing values using forward fill and backward fill techniques
- Removed anomalies and extreme fluctuations
- Performed data cleaning and transformation for time-series analysis

---

## 2. Feature Engineering
Generated multiple predictive features including:
- Lag features
- Daily returns
- Logarithmic returns
- Rolling statistics
- Market trend indicators

---

## 3. Markov Chain Modeling
Stock movements were classified into three market states:
- Bullish
- Bearish
- Sideways

Transition Probability Matrices (TPM) were created to:
- Analyze trend transitions
- Estimate next-state probabilities
- Evaluate market risk behavior

### Key Applications
- Trend probability forecasting
- Risk assessment
- Market regime analysis
- Portfolio decision support

---

## 4. Machine Learning Models

### Models Implemented
- XGBoost
- Random Forest

### ML Workflow
- Time-series data preparation
- Training and testing split
- Model training and validation
- Prediction benchmarking
- Performance evaluation

---

# Evaluation Metrics
The forecasting models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics were used to compare model performance and optimize prediction accuracy.

---

# Results

## Markov Chain Model

### Advantages
- Interpretable probabilistic forecasting
- Effective trend transition analysis
- Useful for long-term market behavior understanding

### Limitations
- Limited capability for precise price prediction
- Relies only on current state probabilities

---

## Machine Learning Models

### Advantages
- Higher prediction accuracy
- Better short-term forecasting performance
- Effective handling of non-linear stock market patterns

### Best Performing Model
 XGBoost achieved the best overall performance with:
- Lowest prediction error
- Highest directional accuracy
- Better investment decision support capability

---

# Visualizations Included
- Correlation Heatmaps
- Predicted vs Actual Price Plots
- Transition Probability Matrices
- Trend Distribution Analysis
- Model Performance Comparison Graphs


---

# Future Improvements
- Hybrid Markov + ML forecasting systems
- Real-time stock prediction integration
- Portfolio optimization models
- Deep learning-based forecasting
- Adaptive market regime modeling

---


# License
This project is intended for academic and educational purposes only.
