# 📈 Google Trends Data Analysis — Analytics Keywords in India

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python) ![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green) ![Seaborn](https://img.shields.io/badge/Seaborn-Visualisation-9B59B6) ![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📌 Project Overview

This project analyses Google Trends data for 5 major analytics and data-related search terms in India over 5 years. It covers data quality assessment, anomaly detection, seasonal pattern analysis, regional interest mapping, and business insight generation — all using Google's own public Trends API.

---

## 🎯 Why This Project?

Google Trends is Google's own product — and it provides real, large-scale public data that mirrors how Google's internal analytics teams think about search patterns and user behaviour. This project demonstrates:

- Ability to work with Google's tools and public APIs
- Anomaly detection on real-world time-series data
- Regional data analysis across Indian states
- Translating trend data into business recommendations

---

## 🔍 Keywords Analysed

| Keyword | Why Relevant |
|---------|-------------|
| Data Analytics | Core career skill being studied |
| Machine Learning | AI/ML trend in India |
| Power BI | BI tool used in projects |
| SQL Tutorial | Education-driven search trend |
| Google BigQuery | Google's own data platform |

---

## 📊 Dataset

- **Source:** Google Trends (via `pytrends` Python API)
- **Timeframe:** 5 years of weekly data
- **Geography:** India (national + state-level)
- **Size:** ~260 weekly data points per keyword

---

## 🔧 Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python | Data pipeline & analysis |
| pytrends | Google Trends API wrapper |
| Pandas | Data cleaning & transformation |
| Matplotlib | Time-series & bar charts |
| Seaborn | Correlation heatmap |

---

## 🚀 Key Analyses Performed

### 1. Interest Over Time
5-year weekly trend lines showing how search interest for analytics keywords has grown in India.

### 2. Anomaly Detection
Statistical spike detection using 2-standard-deviation threshold — flags weeks with unusually high search interest (e.g., around major AI announcements or events).

### 3. Seasonality Analysis
Monthly average interest for "Data Analytics" — reveals which months see peak search activity and why.

### 4. Regional Heatmap
State-by-state breakdown of "Data Analytics" interest across India — identifies top talent markets and growth regions.

### 5. Correlation Matrix
Keyword correlation analysis — shows which analytics skills are being searched together, revealing skill bundling patterns in the job market.

---

## 📈 Key Findings

| Finding | Detail |
|---------|--------|
| Fastest growing keyword | Machine Learning (+34% YoY) |
| Highest sustained interest | SQL Tutorial |
| Peak search month | January (Q1 hiring season) |
| Top Indian state | Karnataka (Bengaluru effect) |
| Anomalous spike weeks | 7 total across all keywords |

---

## 💡 Business Recommendations

1. **Hire data talent in January** — peak search month signals active job seekers
2. **Focus recruitment in Karnataka & Maharashtra** — highest regional interest
3. **Invest in ML upskilling** — fastest growing keyword signals future demand
4. **Bundle SQL + Power BI training** — high correlation means professionals seek both together

---

## ▶️ How to Run

```bash
# Clone the repo
git clone https://github.com/your-username/google-trends-analysis

# Install dependencies
pip install pytrends pandas matplotlib seaborn

# Run the analysis
python google_trends_analysis.py

# Or open the notebook
jupyter notebook google_trends_analysis.ipynb
```

**Note:** pytrends uses Google Trends' unofficial API. Run with a small delay between requests to avoid rate limiting (already handled in the code).

---

## 📁 Repository Structure

```
google-trends-analysis/
│
├── google_trends_analysis.py     # Main analysis script
├── google_trends_analysis.ipynb  # Jupyter notebook version
├── trends_data.csv               # Exported trends data
├── regional_data.csv             # State-wise interest data
├── google_trends_analysis.png    # Output visualisation
└── README.md
```

---

## 📸 Output Preview

The script generates a 5-panel visualisation:
- Interest over time (all 5 keywords)
- Average interest bar chart
- Keyword correlation heatmap
- Monthly seasonality chart
- Top Indian states regional bar chart

---

## 👤 Author

**Yennamaneni Sai Kumar**  
B.Tech Data Science | Anurag University, 2025  
📧 Saikumarrao.yennamaneni@gmail.com

---

*This project uses Google's own public Trends data and was built for the Google Data Analytics Apprenticeship portfolio.*
