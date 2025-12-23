# 📈 Stock Price Prediction (Time Series Analysis)

### 🚀 Day 10 of 30: Machine Learning Projects Challenge

**Goal:** Predict the future closing price of a stock (e.g., Apple, Google) based on past trends.
**The Challenge:** Stock market data is noisy and sequential. Unlike standard datasets, the *order* of data matters (Time Series).

---

## 🧐 The Concept: Feature Engineering for Time
To make a standard regression model understand "time," we engineered two key features:
1.  **Moving Averages (MA_50):** We calculated the 50-day average price to capture the long-term trend (Bullish vs. Bearish).
2.  **Target Shifting:** We shifted the price column by `-1` day. This aligns "Today's Data" with "Tomorrow's Price," allowing the model to learn the relationship between the present and the future.

---

## 🛠️ Tech Stack
* **Python**
* **yfinance** (Live Stock Data API)
* **Scikit-Learn** (Linear Regression)
* **Pandas** (Rolling Windows & Time Shifting)
* **Matplotlib** (Visualization)

---

## ⚙️ How to Run
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/TomarBondhuRashed/stock-price-prediction.git](https://github.com/TomarBondhuRashed/stock-price-prediction.git)
    ```
2.  **Install dependencies:**
    ```bash
    pip install numpy pandas scikit-learn matplotlib yfinance
    ```
3.  **Run the script:**
    ```bash
    python stock_predictor.py
    ```

---

## 📊 Results
The model visualizes the **Actual vs. Predicted** price path.
* **Red Line:** AI Predictions
* **Blue Line:** Actual Market Moves

*Note: While the model achieves high accuracy (R² > 95%), stock prediction involves external factors (news, economy) that a simple regression model cannot capture.*

---

## 🤝 Connect
Follow my 30-day coding journey!
* **LinkedIn:** [Your Profile Link]
* **GitHub:** [TomarBondhuRashed](https://github.com/TomarBondhuRashed)
