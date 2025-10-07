
# SPY Price Movement Prediction (2015–2025) 📈

Predicting whether the S&P 500 ETF (SPY) will close **higher or lower the next day** using historical price data. This is a **binary classification problem**:

- **1** → Tomorrow’s close > Today’s close  
- **0** → Tomorrow’s close ≤ Today’s close  

---

## Project Overview

### 1. Data Collection
- Historical SPY data from **2015 to 2025** downloaded using **yfinance**.

### 2. Feature Engineering
- Created financial indicators including:
  - Daily returns  
  - Moving averages (short & long term)  
  - Volatility measures  
  - Momentum indicators  

### 3. Exploratory Data Analysis
- Visualized price trends and return distributions  
- Built a **correlation heatmap** to examine relationships between features and the target  

### 4. Model Preparation
- Split dataset into **training (80%)** and **testing (20%)** sets  
- Preprocessed data for supervised learning  

### 5. Next Steps
- Train and evaluate machine learning models:
  - **Logistic Regression**  
  - **Random Forest**  
  - **LSTM (Long Short-Term Memory networks)**  

---

## Technologies Used
- **Python 3.10**  
- Libraries:
  - `pandas`, `numpy` (data manipulation)  
  - `matplotlib`, `seaborn` (visualization)  
  - `yfinance` (data download)  
  - `scikit-learn` (ML models)  

