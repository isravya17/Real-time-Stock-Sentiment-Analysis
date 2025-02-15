# Real-time Stock Sentiment Analysis

## Project Overview

### **Overview:**  
This project analyzes real-time sentiment from stock news headlines for major tech companies—Apple (AAPL), Amazon (AMZN), Google (GOOG), NVIDIA (NVDA), and Tesla (TSLA)—to understand its impact on stock price fluctuations. By correlating sentiment scores with actual stock movements, the project aims to provide insights that aid investment decisions.

### **Data Sources:**  
- **News Headlines:** Scraped from financial news websites.  
- **Stock Prices:** Fetched using Yahoo Finance API for real-time and historical data.  

### **Approach:**  

1. **Data Collection:**  
   - Scraped news headlines using **BeautifulSoup** and **Requests**.  
   - Retrieved stock prices via **Finwiz API**.  

2. **Sentiment Analysis:**  
   - Applied **VADER’s Sentiment Intensity Analyzer** to calculate compound sentiment scores for each headline.  

3. **Data Processing and Correlation:**  
   - Used **Pandas** for data manipulation and **SciPy** to calculate correlation between sentiment scores and stock prices.  

4. **Visualization:**  
   - Created interactive dashboards using **Plotly** to visualize sentiment trends and price movements.  

## Results

![image](https://github.com/user-attachments/assets/71e52360-ba82-470c-8bf0-82d04c95fe11)

Analyzing the recent stock sentiment data alongside actual price movements for Apple (AAPL), Alphabet (GOOG), NVIDIA (NVDA), Tesla (TSLA), and Amazon (AMZN) from February 12 to February 15, 2025, reveals the following insights:

**1. Apple Inc. (AAPL):**
- **Sentiment Analysis:** Positive sentiment, especially on February 12, driven by news of an AI partnership with Alibaba.
- **Stock Performance:** The stock experienced a modest increase, closing at $244.60 on February 15, up approximately 1.27% from the previous close.

**2. Alphabet Inc. (GOOG):**
- **Sentiment Analysis:** Generally positive sentiment, with notable discussions around increased capital expenditures for AI infrastructure.
- **Stock Performance:** Despite the positive sentiment, the stock saw a slight decline, closing at $186.87 on February 15, down about 0.49%.

**3. NVIDIA Corporation (NVDA):**
- **Sentiment Analysis:** Mixed sentiment due to concerns over AI chip demand and competition.
- **Stock Performance:** The stock showed resilience, closing at $138.85 on February 15, reflecting a 2.63% increase, possibly due to optimism about AI chip demand.
  
**4. Tesla Inc. (TSLA):**
- **Sentiment Analysis:** Positive sentiment, with discussions about CEO Elon Musk's net worth and company performance.
- **Stock Performance:** The stock remained relatively stable, closing at $355.84 on February 15, with a marginal decrease of 0.03%.

**5. Amazon.com Inc. (AMZN):**
- **Sentiment Analysis:** Neutral to slightly positive sentiment, with limited significant news impacting the stock.
- **Stock Performance:** The stock experienced a slight decline, closing at $228.68 on February 15, down approximately 0.73%.

In summary, while positive sentiment, particularly related to AI developments, correlated with stock price increases for companies like Apple and NVIDIA, other factors such as increased expenditures or market dynamics influenced the stock performance of Alphabet, Tesla, and Amazon, leading to slight declines or stability despite favorable sentiment. 
