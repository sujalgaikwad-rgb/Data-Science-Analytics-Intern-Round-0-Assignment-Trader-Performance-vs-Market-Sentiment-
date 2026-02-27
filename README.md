# Trader Performance vs Market Sentiment Analysis

## 📌 Objective

This project analyzes how Bitcoin market sentiment (Fear/Greed) influences trader behavior and performance on Hyperliquid.
The goal is to uncover behavioral patterns and generate actionable trading strategy insights based on sentiment regimes.
---

## ⚙️ Setup Instructions

### 1️⃣ Install Anaconda (Recommended)
Download and install Anaconda:
https://www.anaconda.com/products/distribution

---

### 2️⃣ Install Required Libraries

Open Anaconda Prompt and run:
pip install -r requirements.txt
Or manually install:
pip install pandas numpy matplotlib seaborn scikit-learn

---

## ▶️ How to Run the Project

### Step 1
Open **Anaconda Navigator**

### Step 2
Launch **Jupyter Notebook**

### Step 3
Navigate to the project folder:
Trader_Sentiment_Analysis

### Step 4
Open:
Assignment1.ipynb

### Step 5
Run all cells:
Kernel → Restart & Run All

---

## 📊 Methodology Overview

1. Data Cleaning & Standardization
   - Cleaned column names
   - Converted timestamps to datetime
   - Extracted daily date
   - Removed duplicates

2. Data Alignment
   - Merged trader dataset with sentiment dataset on daily level

3. Feature Engineering
   - Daily PnL per trader
   - Win indicator (profitability bucket)
   - Trade frequency segmentation
   - Average trade size analysis

4. Sentiment-Based Analysis
   - Compared performance across:
     - Extreme Fear
     - Fear
     - Neutral
     - Greed
     - Extreme Greed

5. Trader Segmentation
   - Frequent vs Infrequent traders
   - Performance comparison across regimes

6. Bonus (Optional)
   - Predictive model for profitability bucket
   - K-Means clustering for behavioral archetypes

---

## 🔎 Key Findings

- Infrequent traders consistently outperform frequent traders across most sentiment regimes.
- Performance dispersion is highest during Greed regimes.
- Fear markets show more balanced behavior across segments.
- Trade selectivity appears more important than trade frequency.

---

## 📈 Strategy Recommendations

1. Reduce trade frequency during Greed regimes to avoid overtrading bias.
2. Increase selectivity and capital allocation to high-conviction trades during Extreme Greed.
3. Maintain disciplined risk management during Fear regimes.

---

## 🧠 Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 👩‍💻 Author
Sujal Gaikwad
Data Science Internship Assignment  
Trader Behavior & Sentiment Analysis
