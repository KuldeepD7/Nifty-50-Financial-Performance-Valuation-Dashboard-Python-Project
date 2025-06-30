# Nifty-50-Financial-Performance-Valuation-Dashboard-Python-Project

## 📊 Project objective

This project focuses on analyzing customer purchasing behavior for an e-commerce business to segment customers and uncover actionable revenue optimization opportunities. Using SQL, the project performs a deep dive into customer metrics like Recency, Frequency, and Monetary value (RFM), purchase trends, return behavior, and demographic insights.

---

## Objective

To analyze and visualize the financial performance and valuation of Nifty 50 companies
 by leveraging key financial indicators such as P/E ratio, ROE, ROCE, 
market capitalization, quarterly profit and sales growth, and dividend yield.The goal is to identify high-performing, consistently growing, and 
potentially undervalued companies by building an interactive dashboard using Power Bi, 
And Python for actionable financial insights.


---

## Dataset Description

- **File Name**: `Nifty 50.csv`
- **Total Columns**: 12 
- **Key Fields**:
  - `Company Name`, `CMP`, `PE Ratio`, `Mar Cap`
  - `Diviend Yield`, `Net Profit Qtr`, `Qtr Profit`
  - `Sales Qtr`, `Qtr Sales`, `ROCE %`, `ROE %`

---

## Tools Used

- **Python**: Pandas, Numfy, Metplotlib, Seaborn
- **Data Preparation**: CSV via import
- **Visulization**: Power Bi for visuals


---
## 🧰 Tools & Technologies Used

| Tool        | Purpose                          |
|-------------|----------------------------------|
| Python      | Data cleaning and transformation |
| Pandas      | Data analysis and preprocessing  |
| SQL (SQLite)| Querying insights from cleaned data |
| Power BI    | Dashboard and visualization      |
| Screener.in | Financial data source            |

---

## 📁 Dataset

The dataset was exported from [Screener.in](https://www.screener.in/) and manually filtered to include Nifty 50 companies. It contains financial metrics such as:

- Company Name
- CMP (Current Market Price)
- P/E Ratio
- Market Capitalization
- Dividend Yield (%)
- Net Profit (Quarter)
- Quarterly Profit Growth (%)
- Quarterly Sales and Sales Growth (%)
- ROCE (%)
- ROE (%)

---

## ❓ Problem Statement

Investors often face difficulty in evaluating and comparing financial data across multiple companies. This project solves that by building a visual, data-driven dashboard that highlights:

- Undervalued stocks with strong fundamentals
- High-growth and high-profit companies
- Industry comparisons within the finance domain (banks, NBFCs, insurance)
- Relationships between profitability and valuation

---

## 🔍 SQL Insight Questions

The cleaned dataset was imported into SQL for querying key insights:

### 📊 Valuation Analysis
- Top 5 companies with lowest P/E ratios
- Companies with P/E < 20 and ROE > 15%
- Highest dividend yield performers

### 💰 Profitability
- Companies with highest ROE and ROCE
- Companies with ROE > 20% and low P/E

### 📈 Growth
- Companies with >10% quarterly profit & sales growth
- Profit and sales trend comparison between NBFCs and Banks

### 🏦 Domain-Specific (Finance)
- Average ROE across banking, NBFC, and insurance
- Top financial companies by ROE and market cap

---

## 📈 Power BI Dashboard Features

- KPI cards for average ROE, ROCE, P/E ratio
- Bar charts for top 10 companies by ROE, ROCE, Dividend Yield
- Scatter plot: ROE vs. P/E ratio (bubble size = Market Cap)
- Filters for sector, market cap, and performance bands
- Conditional formatting in tables for quick insights

---

## 📷 Dashboard Preview

> *(Add screenshot of your Power BI dashboard here once it's ready)*

---

## 🚀 How to Run This Project

1. Clone this repository  
2. Download or export the dataset from Screener.in  
3. Run the Python script for cleaning and preprocessing  
4. Load cleaned data into a local SQL database (SQLite recommended)  
5. Connect Power BI to the SQL DB or cleaned Excel  
6. Build or open the dashboard using the `.pbix` file

---

## 📚 Future Improvements

- Add time series analysis (multi-quarter trends)
- Automate data collection using APIs or web scraping
- Compare with broader indices like Nifty Next 50
- Create a Streamlit web app version

---

## 👨‍💼 Author

**Kuldeep Dwivedi**  
Aspiring Data Analyst | Python • SQL • Power BI  
[LinkedIn](https://www.linkedin.com) *(Add your link)*  
[Portfolio](https://yourportfolio.com) *(Optional)*

---

## 📄 License

This project is intended for educational purposes only. Financial data is sourced from public platforms and may be subject to change.






