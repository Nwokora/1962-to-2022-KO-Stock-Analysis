# 📈 Analysis of Coca-Cola (KO) Stock Performance from 1962 to 2022.
Analysis of Coca-Cola Inc. (KO) daily OHLCV data highlights a robust 60-year growth path (1962 to 2022) that evolved from sparse trading volumes to elevated monthly averages, demonstrating exceptional resilience across diverse market cycles.
It narrows down the trends to show steady performance over decades. Power BI visuals make it clear, with optimised area charts that track price and volume growth, clustered columns that break down monthly and quarterly patterns, and KPI cards that highlight win rates and returns.
Skills demonstrated include: Power BI dashboard design, DAX measure creation (AVERAGE, SUM, CALCULATE), cross-filtering interactivity, data transformation, financial visualisation, and critical thinking in matching aggregation trends, making it ideal for financial data analysis and business intelligence.

## 📂 Project Structure
- **/data** – Contains the raw dataset and cleaned/split CSV files used in this project.  
- **/analysis** – Includes PNG charts generated during analysis.  
- **/screenshots** – Screenshots of pivot tables and spreadsheet transformations.  
- **insights.md** – Markdown summary of all key insights extracted from the analysis.  
- **README.md** – This file you’re reading now!

  ## 📊 Tools Used
- Excel (Data Cleaning, Pivot Tables)
- Power BI (Visualizations)
- GitHub (Documentation)
- Markdown (.md files)

## 📊 Business Questions Answered
| Q | Business Question | Visualizations |
|---| ------------------|----------------|
| **Q1** | How has KO volume grown over 60 years? | Stacked Area Chart |
| **Q2** | How does KO volume show quarterly seasonality spread? | Clustered Column Chart  |
| **Q3** | What is the average KO close price by year? | Line Chart |
| **Q4** | What is the volume spread of KO by months? | Clustered Column Chart |
| **Q5** | What is the sum of KO close price by month? | Area Chart |

## 📸 Screenshots
All charts, pivots, and visuals used in this project are stored in the /screenshots/ folder. View screenshots here: (https://github.com/dimma-analytics/antibiotic-resistance-analysis/tree/main/screenshots)

## 📁 Data
This folder contains the datasets used throughout the project:

Raw Dataset – The original Excel file sourced from the European Antimicrobial Resistance Surveillance (EARS) database.
Cleaned Dataset (by Age & Gender) – Processed versions used to create pivot tables and charts for analysis. View datasets here: (https://github.com/dimma-analytics/antibiotic-resistance-analysis/tree/main/data)

## 📊 Analysis
This folder contains all final visualizations and charts generated from the cleaned datasets.
These include resistance trends over time, comparisons by gender, age group, and bacterial species. View charts here: (https://github.com/dimma-analytics/antibiotic-resistance-analysis/tree/main/analysis)

## 🔗 Data Source
European Antimicrobial Resistance Surveillance (EARS) database (Kaggle)


## Table of Contents
- [Project Overview](#project-overview)
- [Files Provided](#files-provided)
- [Data Sources](#data-sources)
- [Tools Used](#tools-used)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis and Data Analysis](#exploratory-data-analysis-and-data-analysis)
- [Analysis Finding](#analysis-finding)
- [Key Insight](#key-insight)
- [Visualization](#visualization)
- [Complete Analysis](#complete-analysis)
- [Recommendation](#recommendation)
- [Author](#author)

## Project Overview
Analysis of Coca-Cola Inc. (KO) daily OHLCV data highlights a robust 60-year growth path (1962 to 2022) that evolved from sparse trading volumes to elevated monthly averages, demonstrating exceptional resilience across diverse market cycles.
It narrows down the trends to show steady performance over decades. Power BI visuals make it clear, with optimised area charts that track price and volume growth, clustered columns that break down monthly and quarterly patterns, and KPI cards that highlight win rates and returns.
Skills demonstrated include: Power BI dashboard design, DAX measure creation (AVERAGE, SUM, CALCULATE), cross-filtering interactivity, data transformation, financial visualisation, and critical thinking in matching aggregation trends, making it ideal for financial data analysis and business intelligence.


## Files Provided    

## Data Sources
Google Stock Dataset (1962–2022) by Kalilur Rahman on Kaggle (15,311 rows × 8 columns). [Download](https://www.kaggle.com/datasets/kalilurrahman/coca-cola-stock-live-and-updated)

## Tools Used
**Excel** 
- Initial data preview and exploration
- Quick validation of row and column distributions

**Power BI**
- Power BI Power Query (data cleaning and transformation)
- Power BI Desktop (analysis, area charts, clustered columns, KPI cards)

**Workflow**: Excel preview → Power Query cleaning & transformation → Power BI analysis, KPI cards, and charts.

## Data Cleaning and Preparation

### Data Quality Assessment

- Verified data types and standardized them for consistency.
- Dropped redundant columns to streamline the dataset.
- Checked for duplicates using Date as the unique identifier (no duplicates found).
- Inspected for missing values (none detected).
- Renamed key columns (e.g., Open → Open Price, High → High Price).
- Confirmed chronological date order date maintained.
  
## Exploratory Data Analysis and Data Analysis  

### DAX Measures
| Measure | Purpose |
|---------|---------|
| Average Close Price | Shows the trend analysis for closing price across all 60 years of trading days |
| Average Daily Volatility | Shows the daily trend behaviour of the stock |
| Close > Open % | Percentage of days stock closed higher than it opened |
| Total Trading Days | Total number of active trading days |

### Analytical Methods Applied
- **Time Series Analysis**: 60-year trends + seasonality
- **Volatility Analysis**: Daily range % of close price
- **Win Rate Analysis**: Close>Open percentage  
- **Aggregation Validation**: Checks the accuracy of measures and calculations
- **Interactive EDA**: Cross-filtering + drill-through


## Analysis Finding
### Key Metrics (KPI Cards)
| **Metric** | **Result** |
|------------|------------|
| **Close > Open %** | **Percentage of profitable days over 60 years (47.94)** |
| **Avg Daily Volatility** | **60-year daily range average (~1.74%)** |

### Business Questions Answered
| Q | Business Question | Visualizations | Key Result |
|---| ------------------|----------------|------------|
| **Q1** | **How has KO volume grown over 60 years?** | **Stacked Area Chart** | **KO saw ~140bn volume of shares traded over 60 years, with 2008 having the highest trading volume of ~6bn** |
| **Q2** | **How does KO volume show quarterly seasonality spread?** | **Clustered Column Chart**  | **KO has an even quarterly spread across the 60 years with the first quarter dominating with ~36bn** |
| **Q3** | **What is the average KO close price by year?** | **Line Chart** | **KO saw ~152,000% growth in average daily close price over 60 years** |
| **Q4** | **What is the volume spread of KO by months?** | **Clustered Column Chart** | **KO achieved almost an even spread across all months, with March having the highest volume of ~13bn in the 60-year run** |
| **Q5** | **What is the sum of KO close price by month?** | **Area Chart** | **August has the highest in the sum of close price with ~16k in total** |


## Key Insight
**The analysis results are summarised as follows:**
#### 1. Massive Trading Scale
Over 60 years (1962-2022) and ~15,000 trading days, Coca-Cola (KO) saw a staggering 140 billion shares traded, with a single-year trading volume of 6 billion shares (about 4.3% of all 60-year volume) in 2008 alone.

#### 2. Trader-Friendly Consistency
Across ~15,000 trading days that span 60 years, KO delivered a ~48% win rate. This means that nearly half of all days closed higher than they opened, and with just 1.74 average daily volatility, making it exceptionally reliable for both short-term and strategic position traders.

#### 3. Consistent Liquidity Base
Monthly volumes evenly distributed (±5% variation) across all 12 months provides consistent liquidity year-round, eliminating seasonal execution risk. Reliable execution 365 days/year

#### 4. Steady Compounding Growth
The average closing price trend of KO shows steady growth projection of ~15,000%, where the shares rose from 0.04 in 1962 to 60.82 in 2022.

## Visualization  
Key insights from GOOG stock data analysis:  
<img src="https://raw.githubusercontent.com/Nwokora/2004-to-2025-Google-Stock-Analysis/main/GOOG%20Stock/GOOG%20Excel%20Preview.png" width="48%" height="300"/>



## Complete Analysis
[GOOG Analysis](<GOOG Stock Analysis.ipynb>)
(interactive charts + code)


## Recommendation
**BUY & HOLD GOOG**  
- Steady 20-year growth proves volatility handling ✅  
- Survived **every crash** (2008, COVID, 2022) ✅  
- Perfect for investors who want to save for future gain ✅

