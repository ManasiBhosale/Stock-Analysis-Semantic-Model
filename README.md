# Stock Market Dashboard with Power BI

## "Design a Semantic Model in Power BI" Certified Project

This project showcases a comprehensive **Power BI dashboard** built using financial data from five major Indian companies over a two-year period. It was developed as part of my exploration into Power BI's modeling and visualization capabilities and earned me the **“Design a Semantic Model in Power BI”** badge.

The dataset used was originally part of an online internship project that sparked my interest in **machine learning**, **feature engineering**, and **data visualization**. Revisiting and reusing this dataset allowed me to reflect on how far I’ve come—and apply what I’ve learned in an engaging and professional way.

---

## Dashboard Overview

### 1. Comparative Analysis (Infosys, ITC, L&T, Reliance, TCS)
- **Time Span**: 2017–2019 (2 years of financial data)
- **Visuals**:
  - Bollinger Bands
  - 21-day vs. 34-day SMA crossover
  - Stock Volatility vs. Nifty 50

### 2. Deep Dive into Hindustan Unilever
- **Time Span**: 2017–2019 (2 years of financial data)
- **Visuals**:
  - VWAP Trends (Volume Weighted Average Price)
  - Daily % Change & Close Price Trends
  - Yearly Trade Volume Analysis
  - Overall Performance & Price Movement Overview

---

## Key Features
- Built with **semantic modeling principles** using calculated columns and measures
- Focused on **interactive filtering**, **time-series insights**, and clean UI/UX
- Designed using a custom theme with consistent color palettes
- Balanced between **technical depth** and **storytelling**

---

## Table Overview

### 1. Hindustan Unilever Table

The table for **Hindustan Unilever** includes detailed stock performance data over time. Below is a snapshot of its key columns:

| Symbol | Series | Date | Prev Close | Open Price | High Price | Low Price | Last Price | Close Price | Average Price | Total Traded Quantity | Turnover | No. of Trades | Deliverable Qty | % Dly Qt to Traded Qty |
|--------|--------|------|------------|------------|------------|-----------|------------|-------------|---------------|-----------------------|----------|---------------|-----------------|------------------------|
| HUL    | EQ     | ...  | ...        | ...        | ...        | ...       | ...        | ...         | ...           | ...                   | ...      | ...           | ...             | ...                    |

*(Note: Other stock tables like Infosys, ITC, L&T, Reliance, and TCS follow the same structure.)*


### 2. Stock Data for Other Companies

The stock data tables for **Infosys**, **ITC**, **L&T**, **Reliance**, and **TCS** follow the same structure as the Hindustan Unilever table. Below is an example of one of the stock tables:

| Symbol | Series | Date | Prev Close | Open Price | High Price | Low Price | Last Price | Close Price | Average Price | Total Traded Quantity | Turnover | No. of Trades | Deliverable Qty | % Dly Qt to Traded Qty |
|--------|--------|------|------------|------------|------------|-----------|------------|-------------|---------------|-----------------------|----------|---------------|-----------------|------------------------|
| INFY   | EQ     | ...  | ...        | ...        | ...        | ...       | ...        | ...         | ...           | ...                   | ...      | ...           | ...             | ...                    |

### 3. Nifty 50 Data

In addition to the individual stock data, a table with **Nifty 50** data is included for comparative analysis:

| Date       | Open | High | Low  | Close | Shares Traded | Turnover (Rs. Cr) |
|------------|------|------|------|-------|---------------|-------------------|
| ...        | ...  | ...  | ...  | ...   | ...           | ...               |



---

## Relationships and Custom Tables

The relationships between the stock tables (Infosys, ITC, L&T, Reliance, TCS) and the Nifty 50 table are visualized below. The connections are made to ensure accurate and consistent data for the analysis, including the creation of custom tables that are essential for the semantic model.

![Relationships & Custom Tables](https://github.com/ManasiBhosale/stock-analysis-semantic-model/blob/6c0035bf5e1ae53548340ce4a2145e5ff0db0dc0/images_bi/Table_Relationships.png)

---

## DashBoard

![DashBoard](https://github.com/ManasiBhosale/stock-analysis-semantic-model/blob/6c0035bf5e1ae53548340ce4a2145e5ff0db0dc0/images_bi/Stock_Dashboard.png)

## Live Demo

![Dashboard Preview](https://github.com/ManasiBhosale/stock-analysis-semantic-model/blob/6c0035bf5e1ae53548340ce4a2145e5ff0db0dc0/images_bi/DashBoard_GIF.gif)

---


## Acknowledgements
- Microsoft Power BI for the platform
- My online internship team for the original dataset
- Community forums and visual guides that helped improve the model

---

## Feedback
If you have ideas to extend this dashboard (e.g., forecasting, sector-based insights, or DAX optimizations), feel free to open an issue or drop a comment!

