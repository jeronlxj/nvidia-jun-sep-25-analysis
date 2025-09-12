# Nvidia Jun to Sep 2025 Analysis

This project downloads NVIDIA (NVDA) **daily** price data for the last 3 months, performs exploratory data analysis, plots prices and returns, and annotates firm-specific events (earnings release, SEC filings, analyst notes, sector news) that may explain price moves.  
NOTE: `yfinance` is being used to fetch price data (internet required), `finnhub` for news data and SEC submissions API for SEC filings data. `yiyanghkust/finbert-tone`, a BERT model finetuned on financial analyst reports, is used to conduct sentiment analysis. 

## Getting Started

To run the application, follow these steps:

1. **Clone the repository**:
   ```
   git clone https://github.com/jeronlxj/nvidia-jun-sep-25-analysis
   cd nvidia-jun-sep-25-analysis
   ```

2. **Download dependencies**:
   - Install the required Python packages:
     ```
     pip install -r requirements.txt
     ```

3. **Running the notebook**:
   - Open the Jupyter Notebook **jeron_report.ipynb**
   - Run as required