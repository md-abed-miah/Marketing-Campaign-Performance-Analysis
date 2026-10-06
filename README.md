
# 📈 Marketing Campaign Performance Analysis

An end-to-end data analysis project focused on evaluating **marketing campaign performance across platforms, campaigns, countries, and time periods** using Python and Pandas.

The goal of this project is to identify **which platforms, campaigns, and markets perform best**, and provide **actionable business recommendations** for budget optimization and performance improvement.

---

## 📌 Project Overview

Marketing teams invest heavily across multiple platforms (Google Search, Google Display, Meta, LinkedIn, Snapchat, TikTok), but not all channels perform equally.

In this project, I analyzed a marketing campaign dataset to evaluate performance using key marketing KPIs such as:

- **CTR** (Click-Through Rate)
- **CPC** (Cost Per Click)
- **CPM** (Cost Per Mille)
- **Conversion Rate**
- **CPA** (Cost Per Acquisition)
- **ROAS** (Return on Ad Spend)

The analysis focuses on identifying high-performing segments and turning those insights into **data-driven marketing decisions**.

---

## 🎯 Business Questions

This project aims to answer:

1. Which platform generates the highest ROAS?
2. What is the overall campaign efficiency?
3. How does performance vary across campaigns?
4. Which countries show the strongest ROAS?
5. Are there seasonal patterns in performance?
6. Which weekdays generate the highest revenue?
7. Where should the business allocate more budget?
8. Which platforms and campaigns need optimization?

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas** — Data cleaning and analysis
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical visualization
- **Jupyter Notebook / Kaggle Notebook**

---

## 📂 Dataset Information

- **Dataset Type:** Simulated marketing campaign data
- **Metrics Covered:** Impressions, Clicks, Spend, Revenue, Conversions
- **Dimensions:** Platform, Campaign, Country, Date, Weekday
- **Purpose:** Analytical and portfolio demonstration

> ⚠️ **Note:** The dataset is simulated and used only for analytical and portfolio purposes.

---

## 🧹 Data Cleaning

Before analysis, the following preprocessing steps were performed:

- Converted date columns to proper datetime format
- Checked for missing values and duplicates
- Verified data types and descriptive statistics
- Created derived columns for CTR, CPC, CPA, CPM, Conversion Rate, and ROAS
- Grouped data by platform, campaign, country, month, and weekday

---

## 📈 Exploratory Data Analysis

### 1. Platform Performance

**Google Search** emerged as the strongest-performing platform:

| Metric | Value |
| :--- | :--- |
| Revenue | $10.36M |
| Spend | $2.74M |
| ROAS | 3.78 |
| Conversion Rate | 1.88% |
| CPA | $12.66 |

Other platforms (Google Display, LinkedIn, Meta, Snapchat, TikTok) showed lower ROAS compared to Google Search.

---

### 2. Overall Campaign Efficiency

| Metric | Value |
| :--- | :--- |
| Overall ROAS | 1.13 |
| Overall Conversion Rate | 1.26% |
| CPA | $39.15 |
| CTR | 1.51% |

Overall efficiency was relatively low, indicating room for optimization.

---

### 3. Campaign-Level Performance

Campaign performance varied significantly.

- The **top campaign** achieved a ROAS of **81.58**
- Many campaigns performed far below the overall average
- This indicates a wide gap between efficient and inefficient campaigns

---

### 4. Country-Level Performance

- **Oman, Lebanon, and Kuwait** showed relatively higher ROAS
- **Qatar** showed the lowest ROAS among the listed countries
- This suggests market-level differences in campaign effectiveness

---

### 5. Monthly Performance Trends

- Higher ROAS values were observed mainly during **October–December**
- **November 2024** recorded the highest monthly ROAS at **2.03**
- Seasonal patterns may influence campaign performance

---

### 6. Weekday Performance

| Weekday | Revenue |
| :--- | :--- |
| Thursday | $2.29M (Highest) |
| Sunday | $1.61M (Lowest) |

Weekday-level differences suggest opportunities for time-based budget optimization.

---

## 📊 Visualizations

The project includes visualizations for:

- Platform-wise Revenue and ROAS
- Campaign-wise ROAS comparison
- Country-wise ROAS
- Monthly ROAS trends
- Weekday revenue distribution
- Overall KPI summary dashboard

---

## 💡 Key Business Insights

### 1. Google Search is the strongest-performing platform
Google Search generated **$10.36M revenue** from **$2.74M spend**, with a ROAS of **3.78** and a conversion rate of **1.88%**.

### 2. Overall campaign efficiency is relatively low
Overall ROAS of **1.13** and conversion rate of **1.26%** suggest significant optimization opportunities.

### 3. Campaign performance varies significantly
The top campaign achieved a ROAS of **81.58**, far above the overall average.

### 4. Country performance varies
**Oman, Lebanon, and Kuwait** showed higher ROAS, while **Qatar** showed the lowest.

### 5. Performance is stronger in some months
Higher ROAS was observed mainly during **October–December**, with **November 2024** reaching **2.03**.

### 6. Weekday performance differs
**Thursday** generated the highest revenue ($2.29M), while **Sunday** generated the lowest ($1.61M).

---

## 📋 Summary of Key Findings

| Factor | Best Performer | Insight |
| :--- | :--- | :--- |
| Platform | Google Search | ROAS 3.78 |
| Campaign | Top Campaign | ROAS 81.58 |
| Country | Oman, Lebanon, Kuwait | Higher ROAS |
| Month | November 2024 | ROAS 2.03 |
| Weekday | Thursday | Revenue $2.29M |

---

## 🎯 Business Recommendations

### 🔹 1. Prioritize High-Performing Platforms
Allocate more budget to **Google Search** campaigns while monitoring performance closely.

### 🔹 2. Optimize Underperforming Platforms
Review targeting, creative strategy, and placements for **Google Display, LinkedIn, Meta, Snapchat, and TikTok**.

### 🔹 3. Optimize Campaigns Based on Efficiency
Scale campaigns with strong ROAS and CPA. Review low-performing campaigns for inefficient spending.

### 🔹 4. Use Market-Level Budget Allocation
Allocate budget based on **ROAS, CPA, and conversion rate** rather than revenue alone.

### 🔹 5. Consider Seasonal Performance Patterns
Plan seasonal campaigns and budgets around historically stronger periods (October–December).

### 🔹 6. Monitor Performance Continuously
Track CTR, CPC, conversion rate, CPA, and ROAS regularly for data-driven decisions.

### 🎯 Overall Recommendation
Adopt a **performance-based optimization strategy** focused on:
- Scaling efficient campaigns and platforms
- Reducing inefficient spending
- Continuously evaluating performance across markets and time periods

---

## 🧠 Conclusion

This marketing campaign performance analysis examined campaign, platform, country, and time-based performance using key KPIs such as **CTR, CPC, Conversion Rate, CPA, and ROAS**.

The analysis revealed significant performance differences across platforms, campaigns, markets, and time periods. **Google Search** demonstrated strong conversion efficiency and ROAS, while several other platforms showed clear opportunities for optimization.

The findings highlight the importance of **performance-based budget allocation** and **continuous KPI monitoring**.

Overall, this project demonstrates how **Python and Pandas** can be used to transform marketing data into actionable business insights and support data-driven marketing decisions.

---

## 📂 Project Structure

```text
marketing-campaign-performance-analysis/
│
├── Marketing_Campaign_Analysis.ipynb
├── marketing_campaign_data.csv
├── README.md
└── images/
    ├── platform_roas.png
    ├── campaign_roas.png
    ├── country_roas.png
    ├── monthly_roas.png
    ├── weekday_revenue.png
    └── final_dashboard.png

🚀 Future Improvements
Build a machine learning model to predict campaign ROAS

Feature importance analysis for high-performing campaigns

Country-level forecasting

Interactive dashboard using Power BI or Tableau

A/B testing simulation for campaign optimization

Budget allocation optimization model

🧠 What I Learned
Through this project, I practiced:

Data cleaning with Pandas

Marketing KPI calculation (CTR, CPC, CPA, ROAS)

Exploratory Data Analysis (EDA)

Group-by and pivot-based analysis

Customer and market segmentation

Data visualization with Matplotlib and Seaborn

Translating analytical findings into business recommendations

📝 Final Notes
The analysis covers campaign, platform, country, and time-based performance.

Key KPIs include CTR, CPC, Conversion Rate, CPA, CPM, and ROAS.

Insights and recommendations are based on the analyzed dataset.

The dataset is simulated and used for analytical and portfolio purposes.

The notebook was reviewed for clarity, consistency, and reproducibility.

👨‍💻 Author
Md. Abed Miah
Data Analyst | Python & Excel Dashboard Developer

📧 oficialabed@gmail.com
📱 +880 1731122699
🔗 LinkedIn
💻 GitHub

⭐ If you find this project useful, feel free to explore the notebook and share your feedback.

