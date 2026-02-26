# 🛒 Walmart Sales Analysis & ML Forecasting

> End-to-end data analysis project combining Python, Machine Learning, Excel, and Power BI to analyze and forecast weekly revenue across 45 Walmart stores (2010–2012).

---

## 📌 Project Overview

This project analyzes **6,435 weekly sales records** across 45 Walmart stores to:
- Identify revenue drivers (holidays, fuel price, CPI, unemployment, temperature)
- Build a **Machine Learning model** to predict weekly revenue
- Detect stores with a **profit gap** (predicted vs actual revenue)
- Visualize insights through an interactive **Power BI dashboard**

---

## 🗂️ Repository Structure

```
walmart-sales-analysis/
│
├── MLtraining.ipynb          # Python notebook: EDA + ML model (Random Forest)
├── Walmart_Sales.csv         # Raw dataset (45 stores, weekly data)
├── Walmart_ML_Results.csv    # Output: actual vs predicted revenue + profit gap
├── vgsales.csv               # Supporting dataset
│
├── visuals/
│   ├── p bi.png              # Power BI dashboard screenshot
│   ├── ml excel.png          # Excel analysis screenshot
│   ├── py.png                # Python output screenshot
│   └── walmart_tree_logic.png # Decision tree logic visualization
│
└── p bi dashboard.pbix       # Power BI dashboard file
```

---

## 🔧 Tools & Technologies

| Tool | Usage |
|------|-------|
| **Python** (pandas, scikit-learn) | EDA, feature engineering, ML model |
| **Random Forest Regressor** | Weekly revenue prediction |
| **Power BI** | Interactive dashboard & KPIs |
| **Excel** | Pivot tables, quarterly analysis |

---

## 🤖 Machine Learning Model

- **Algorithm:** Random Forest Regressor
- **Features:** Store ID, Holiday Flag, Temperature, Fuel Price, CPI, Unemployment
- **Target:** Weekly Revenue
- **Output:** Predicted revenue + Profit Gap per store per week

The `Profit_Gap` column highlights weeks where actual revenue deviated from the model's prediction — useful for anomaly detection and store performance benchmarking.

---

## 📊 Power BI Dashboard

The dashboard covers:
- Weekly revenue trends by store
- Holiday vs non-holiday revenue comparison
- Quarterly revenue averages and fuel price correlation
- Store-level performance ranking

> 📁 Open `p bi dashboard.pbix` in Power BI Desktop to explore interactively.

---

## 📈 Key Insights

- **Holiday weeks** generate significantly higher revenue, especially in Q4
- **Fuel price** and **CPI** show negative correlation with sales in lower-income store zones
- Top-performing stores (1–10) consistently outperform the 45-store average by 30–40%
- The ML model identifies underperforming weeks where revenue fell short of predicted potential

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/karimelkarkoubi/walmart-sales-analysis.git

# Install dependencies
pip install pandas scikit-learn matplotlib seaborn jupyter

# Launch notebook
jupyter notebook MLtraining.ipynb
```

---

## 👤 Author

**Karim El Karkoubi**  
Master's in Languages & Management | Data Analysis Enthusiast  
📍 France | Open to opportunities in France 🇫🇷, Switzerland 🇨🇭, Japan 🇯🇵

[![GitHub](https://img.shields.io/badge/GitHub-karimelkarkoubi-181717?style=flat&logo=github)](https://github.com/karimelkarkoubi)
