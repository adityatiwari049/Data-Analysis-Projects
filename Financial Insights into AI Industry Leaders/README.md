📊 AI Financial Market Analysis with Python
Overview
This project provides an in-depth analysis of AI-driven companies and their financial performance over time, focusing on R&D spending, AI revenue, and market impact. Using Python’s data science ecosystem, we explore patterns, trends, and correlations in the financial growth of companies like OpenAI, Google, and Meta.

The project is designed for analysts, researchers, and AI enthusiasts who want a clear, interactive, and visual understanding of the AI financial market.

🔍 Key Features
Data Cleaning & Preprocessing

Converted Date from object to datetime format.

Checked and handled missing values.

Created new features such as Year.

Exploratory Data Analysis (EDA)

Summary of company-wise R&D spending and AI revenue.

Identification of major events like GPT-4 release and their stock impact.

Visualizations

Bar charts showing total R&D spending and AI revenue per company.

Interactive Plotly bar chart for revenue comparisons.

Dual subplot to compare revenue and spending side-by-side.

Market Insights

Spending vs. revenue patterns reveal profitability trends.

Event-based filtering to see financial response to major AI releases.

🛠️ Tech Stack
Python Libraries:

pandas → Data handling & preprocessing

numpy → Numerical operations

matplotlib & seaborn → Static visualizations

plotly.express → Interactive plots

📂 Dataset
Source: ai_financial_market_daily_realistic_synthetic.csv

Shape: 10,959 rows × 7 columns

Columns:

Date – Transaction/record date

Company – Company name (OpenAI, Google, Meta)

R&D_Spending_USD_Mn – Research and development spending (in million USD)

AI_Revenue_USD_Mn – AI revenue (in million USD)

AI_Revenue_Growth_% – Yearly percentage revenue growth

Event – Significant AI-related events (e.g., GPT-4 release)

Stock_Impact_% – Stock market impact in %

📊 Example Insights
R&D Spending (Total in $Bn)

Google: 423.34

Meta: 264.53

OpenAI: 26.48

AI Revenue (Total in $Bn)

Google: 284.50

Meta: 189.62

OpenAI: 9.46

Event Spotlight: GPT-4 release (March 14, 2023) saw 304.57% AI revenue growth for OpenAI and 15.2% stock impact.

🚀 How to Run
Clone the repository

bash
Copy
Edit
git clone https://github.com/adityatiwari049/ai-financial-analysis.git
cd ai-financial-analysis
Install dependencies

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn plotly
Place the dataset ai_financial_market_daily_realistic_synthetic.csv in the project directory.

Run the notebook

bash
Copy
Edit
jupyter notebook
Open the provided .ipynb file and execute the cells.

📌 Future Improvements
Add time-series forecasting for AI revenue growth.

Include profitability ratios and ROI metrics.

Implement real-time data updates from financial APIs.

📜 License
This project is licensed under the MIT License.
