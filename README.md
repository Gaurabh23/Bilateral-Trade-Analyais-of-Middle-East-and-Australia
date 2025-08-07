# Data-Driven Analysis of Bilateral Trade Between Australia and the Middle East (2019–2023)

This project presents a comprehensive data analytics pipeline to examine **bilateral trade relationships between Australia and Middle Eastern countries** from 2019 to 2023. It leverages real-world trade data to extract insights on trade volumes, product flows, growth trends, and imbalances, supporting strategic decision-making for economic and policy planning.

---

## Objectives
- Clean, integrate, and analyze trade datasets from multiple sources
- Explore trade trends at regional, country, and product levels
- Identify growth opportunities and trade imbalances
- Cluster products/countries based on trade behavior
- Forecast future trade values using data-driven models

---

##  Dataset Summary
- Source: Provided by client
- Files include:
  - One **master trade dataset** between Australia and the Middle East
  - **Individual files** for each Middle Eastern country (e.g., UAE, KSA, Qatar)
- Final merged and cleaned dataset: `cleaned_trade_master.csv`

---

## Phase 1: Data Cleaning & Preparation
- Combined multiple trade files into a unified dataset
- Standardized column names and formats
- Removed missing, duplicated, or inconsistent records
- Engineered features like:
  - 5-year and 1-year growth rates
  - Trade balance
  - Product-level concentration and average tariff

---

## Phase 2: Exploratory Data Analysis (EDA)

Structured into 3 insight-driven layers:

### Layer 1: Regional Overview
- Pareto chart: Top countries contributing to trade
- Bubble chart: Top traded product categories by country

### Layer 2: Country-Level Deep Dive
- Heatmap of UAE’s top products by value, growth, and balance
- Scatterplot: Growth vs. trade balance for UAE

### Layer 3: Product-Centric Insights
- Heatmap of top 10 products across all countries
- Forecast candidates bubble chart: growth vs. trade value

### Final Insight: Trade Surplus vs. Deficit
- Horizontal bar chart to visualize products with the highest trade surpluses and deficits

---

## Phase 3: Advanced Analytics (Upcoming)

### Clustering
- Cluster products or countries based on trade metrics
- Techniques: K-Means, DBSCAN, Hierarchical Clustering

### Forecasting
- Time series or regression models to predict future trade values
- Candidate models: ARIMA, XGBoost, Prophet

### Pattern Mining
- Discovering co-occurrence patterns of traded goods
- Association rule mining or FP-Growth

---

## Sample Insights (from EDA)
- UAE and Saudi Arabia are dominant trade partners
- Machinery, aluminum, and medical instruments are key export items
- Several food/agri-products show persistent trade deficits
- Strong candidates for growth include tech and chemical products

---

## 🛠 Tech Stack
| Tool         | Usage                              |
|--------------|-------------------------------------|
| **Python**   | Core data analysis language         |
| **Pandas**   | Data cleaning & transformation      |
| **Matplotlib / Seaborn** | Visual analytics & EDA |
| **Jupyter Notebook** | Interactive analysis        |
| **Scikit-learn** | (upcoming) Clustering, modeling |
| **GitHub**   | Version control & collaboration     |

---

## 📁 Folder Structure
```bash
├── data/
│   ├── raw/                    # Original trade files
│   └── cleaned_trade_master.csv
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda_visualization.ipynb
│   └── 03_clustering_forecasting.ipynb
├── visuals/
│   └── eda_charts.png
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run Locally
1. Clone this repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

---

