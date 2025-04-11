# Trend Lines on BNB/USDT (1h)

This project focuses on the automatic detection of **trend lines**, **support and resistance levels**, and **psychological price zones** based on historical price data for the **BNB/USDT** pair (1-hour intervals).

---

## Project Structure

- `BNBUSDT_1h_20171106_20250328.csv`  
  OHLC (Open, High, Low, Close) data at 1-hour frequency from November 2017 to March 2025.

- `Project_Trend_lines.ipynb`  
  Main notebook containing the full logic: data loading, peak detection, trend extraction, support/resistance fitting, scoring, and visualization.

---

## Goals

- Automatically detect:
  - Local trends (based on moving averages and peaks)
  - Support and resistance lines (local and global)
  - Psychological levels (frequently hit price zones)

- Plot **interactive candlestick charts** using Plotly

- Implement a **scoring system** to evaluate the reliability of detected trend lines

---

## Tech Stack

- Python 3.10+
- `numpy`, `pandas`, `scipy`, `plotly`
- `scikit-learn` (Theil-Sen regression for robust line fitting)
- `plotly.graph_objects` for candlestick + overlay visualizations

---

## How to Run the Project

1. Clone the repo:
   ```bash
   git clone https://github.com/Alexandro-Biz24/your-repo-name.git
   cd your-repo-name
