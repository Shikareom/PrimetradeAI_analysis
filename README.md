# Trader Performance vs Market Sentiment Analysis

##  Objective
The goal of this project is to analyze how market sentiment (Fear vs Greed) affects trader behavior and performance.

---

##  Datasets Used

1. Bitcoin Market Sentiment Dataset  
   - Contains daily classification: Fear or Greed  

2. Historical Trader Data (Hyperliquid)  
   - Includes trade details such as account, price, size, side, and profit/loss  

---

##  Methodology

### 1. Data Loading
Both datasets were loaded using Python and inspected.

### 2. Data Cleaning
- Removed duplicate rows  
- Handled missing values  
- Cleaned column names  

### 3. Data Transformation
- Converted timestamps into datetime format  
- Extracted date from timestamp  

### 4. Data Merging
- Merged datasets using the date column  

### 5. Feature Engineering
Created:
- Win/Loss column  
- Daily PnL  
- Trade count  
- Average trade size  
- Long/Short ratio  

### 6. Analysis
- Compared performance (PnL, win rate) across Fear and Greed  
- Studied trading behavior (trade count, size)  
- Used simple segmentation based on trade size  

### 7. Visualization
Used basic charts:
- Boxplots  
- Bar charts  

---

##  Key Insights

1. Traders perform slightly worse during Fear periods  
2. More trades happen during Greed, but profitability does not improve much  
3. Larger trades show higher risk and variability  

---

##  Strategy Recommendations

1. Reduce trade size during Fear markets to manage risk  
2. Avoid overtrading during Greed and focus on better trade decisions  

---

##  How to Run

1. Clone the repository  

2. Install dependencies: pip install pandas numpy matplotlib seaborn

3. Open the notebook and run all cells 

