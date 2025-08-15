# 📊 AI Financial Market Analysis with Python

## Overview
This project analyzes AI-driven companies and their financial performance over time, focusing on **R&D spending**, **AI revenue**, and **market impact**.  
We use Python's data science tools to find patterns, trends, and insights into how companies like **OpenAI, Google, and Meta** are investing in AI.

---

## 🔍 Features
- **Data Cleaning & Processing**
  - Converted dates to datetime format.
  - Checked and handled missing values.
  - Extracted year for analysis.
- **Exploratory Data Analysis**
  - Summarized R&D spending and AI revenue.
  - Studied financial impact of major AI events (e.g., GPT-4 release).
- **Visualizations**
  - Bar charts for total R&D spending and AI revenue.
  - Interactive Plotly charts for company comparison.
  - Dual subplots for spending vs. revenue.
- **Insights**
  - Correlation between AI investments and revenue growth.
  - Stock market impact of major AI developments.

---

## 🛠 Tech Stack
- **Python Libraries:**
  - `pandas` – Data handling
  - `numpy` – Numerical operations
  - `matplotlib` & `seaborn` – Static visualizations
  - `plotly.express` – Interactive visualizations

---

## 📂 Dataset
- **File:** `ai_financial_market_daily_realistic_synthetic.csv`
- **Shape:** 10,959 rows × 7 columns
- **Columns:**
  - `Date` – Record date
  - `Company` – Company name
  - `R&D_Spending_USD_Mn` – R&D spending in million USD
  - `AI_Revenue_USD_Mn` – AI revenue in million USD
  - `AI_Revenue_Growth_%` – Annual revenue growth (%)
  - `Event` – Major AI-related event
  - `Stock_Impact_%` – Stock price change (%)

---

## 📊 Example Insights
- **R&D Spending (Total in $Bn)**
  - Google: 423.34
  - Meta: 264.53
  - OpenAI: 26.48
- **AI Revenue (Total in $Bn)**
  - Google: 284.50
  - Meta: 189.62
  - OpenAI: 9.46
- **Event Example:** GPT-4 release boosted OpenAI’s AI revenue growth by 304.57% with a 15.2% stock impact.

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ai-financial-analysis.git
   cd ai-financial-analysis
