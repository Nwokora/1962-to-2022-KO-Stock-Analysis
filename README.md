# 💹 Coca-Cola (KO) Stock Performance Analysis (1962-2022)

## 📌 Overview
Analysis of Coca-Cola Inc. (KO) daily OHLCV data highlights a robust 60-year growth path (1962 to 2022) that evolved from sparse trading volumes to elevated monthly averages. It narrows down the trends to show steady performance over decades. Power BI visuals use optimized charts to track price and volume growth by month, quarter, and year, and KPI cards to highlight win rates and returns.

## 🎯 Objective
To analyze KO’s historical market performance from 1962 to 2022 by examining trading volume, average closing price, trading consistency, and volatility patterns to understand its short-term and long-term value creation, liquidity, and stability.

## 📊 Analysis Questions
1. Average KO volume by year.
2. Average KO volume by month.
3. Average KO close price by year.
4. Average KO close price by quarter.
5. Average KO close price by month.

## 🛠️ Tools Used
-  Excel (Initial data preview and quick validation of rows & columns distributions)
-  Power Query (Data cleaning and preparation)
-  Power BI (Analysis visualization)

## 🔗 Data Source
Coca-Cola Stock Dataset (1962–2022) by Kalilur Rahman (Kaggle).
**[Dataset Source](https://www.kaggle.com/datasets/kalilurrahman/coca-cola-stock-live-and-updated)**

## 🧹 Data Cleaning and Preparation
- Standardized column data types for consistency and analysis.
- Checked for duplicates (none were found.)
- Checked for missing values (none were found.)
- Renamed Open, High, Low, and Close with a Price prefix for clarity.
- Created key measures such as Average Close Price, Average Daily Volatility, Total Trading Days, and related metrics.

## 📉 Analysis
- **Volume of KO Traded** – This analysis shows the total trading activity of KO over the selected period, helping to indicate overall market interest and liquidity. The result showed a total volume of 140 billion shares traded over 60 years.
- **Total Trading Days** – This analysis shows the total trading days covered in the dataset, spanning ~15,000 trading days over the full period under review.
- **Close > Open (%)** – This metric shows the percentage of trading days when the closing price was higher than the opening price, reflecting how often KO ended the day positively. KO closed higher than it opened on 48% of trading days.
- **Average Daily Volatility** – This metric measures the average amount KO’s price moved each day. 1.74 Avg Daily Volatility shows a moderate and relatively stable stock over the period.
- **Average Volume by Year Analysis** – This analysis examines how KO’s trading volume changed over 60 years, from 1962 to 2022. The average annual volume rose from 1,371,885.71 shares in 1962 to 16,810,583.01 shares in 2022. The highest average volume occurred in 2008, reaching 25,264,216.60 shares.
- **Average Volume by Month Analysis** –This analysis examines how KO’s trading volume varies across the months of the year. The result shows monthly volumes are nearly even, with only about ±5% variation across all 12 months.
- **Average Close Price by Year** – This analysis examines KO’s average closing price over time to highlight the stock’s growth trend across the study period. The price rose from 0.04 in 1962 to 60.86 in 2022, an increase of about 152,050%.
- **Average Closing Price by Quarter** – This analysis examines KO’s average closing price across each quarter, helping to reveal short-term performance trends within the year.
- **Average Closing Price by Month** – This analysis examines KO’s average closing price across each month, helping to identify recurring seasonal patterns and short-term price trends.

## 🔭 Visualizations
<img width="785" height="327" alt="Screenshot 2026-05-26 093541" src="https://github.com/user-attachments/assets/8491436a-b8cd-446f-889c-33696120fab3" />

**1962-2022 KO Market Performance Summary highlights KO’s long-term trading behaviour, liquidity, and price stability over the 60 years. The KPIs capture total trading volume, the number of trading days analyzed, the percentage of days the stock closed above its opening price, and the average daily volatility. Together, they provide a concise view of KO’s market activity and show how consistently the stock has performed over time.**

<img width="761" height="304" alt="image" src="https://github.com/user-attachments/assets/6749bc76-4351-4b6c-b892-0b3190fa0043" />

**Average Volume Traded by Year shows that KO’s trading activity increased substantially over time, rising from 1,371,885.71 in 1962 to 16,810,583.01. The peak in 2008 at 25,264,216.60 suggests unusually strong market participation during that year.**

<img width="759" height="302" alt="Screenshot 2026-05-25 095000" src="https://github.com/user-attachments/assets/eb327dd5-8901-4a60-8fe0-6b51ccd44f75" />

**Average Close Price by Year highlights KO’s remarkable long-term price growth, rising from 0.04 in 1962 to a peak of 60.86 in 2022. This steady increase reflects the stock’s enduring strength and long-term value expansion.**

## 💡 Key Insights
Over the 60 years analysed, KO demonstrated exceptional long-term resilience and value creation. The stock rose from 0.04 to 60.86, representing a growth of about 152,050%, while maintaining an average daily volatility of just 1.74%. This combination of strong appreciation and relatively modest volatility suggests a stock that has delivered substantial returns without excessive instability.

KO also demonstrated consistently strong market participation. About 140 billion shares were traded over the period. The stock closed above its open on roughly 48% of trading days, and monthly volume remained highly stable, varying by only about ±5%.

In practical terms, these metrics suggest that KO has enjoyed broad global acceptance, likely supported by the enduring strength of its beverage brands and its reputation as a stable, highly liquid stock. The consistency in volume, modest volatility, and strong long-term appreciation all indicate a stock that has been attractive to both short-term traders and long-term investors.
**[See Insights Here](https://github.com/nwokora/1962-to-2022-ko-stock-analysis/blob/main/insights.md)**

## 📂 Repository Layout  
- **📈 analysis charts** – Final analysis visuals (PNG)
- **🗄️ dataset** – Raw dataset and cleaned CSV files
- **📋 group tables** – Pandas aggregated tables in CSV files
- **⚙️ process charts** – Technical work steps visual (PNG)
- **📖 README.md** – Project overview
- **🔎 Analysis Findings** – All metrics and findings from the analysis
- **💡 insights.md** – All insights from analysis
