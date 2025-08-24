# 🍹 Beverage Sales Analytics Project

## 📊 Overview
This project analyzes **synthetic beverage sales data** to generate business insights, build forecasting models, and create an interactive **Power BI dashboard**.  
It combines **Data Science + Business Intelligence + Simulation** to help optimize pricing, promotions, and customer strategies.

---

## 🔑 Features
- **Exploratory Data Analysis (EDA)**: Sales trends, revenue drivers, category breakdowns.
- **Forecasting**: Prophet-based time series models for demand prediction.
- **Customer Segmentation**: Identifies repeat buyers, loyal customers, and profitability scores.
- **Product Affinity Analysis**: Detects products frequently bought together for bundling.
- **Discount & Price Simulations**: What-if analysis for dynamic pricing.
- **Power BI Dashboard**: Interactive visual reports with KPIs and insights.

---

## Large Files & Datasets

Some files in this project are too large to be stored directly on GitHub 
(e.g., Power BI reports and large CSV datasets). 

Instead, they are hosted externally.  
Please download them from the following links and place them in the correct folders:

- [dashboard/reports.pbix](https://drive.google.com/your-link-here) → `dashboard/reports.pbix`
- [data/processed/main_data.csv](https://drive.google.com/your-link-here) → `data/processed/main_data.csv`
- [data/synthetic_beverage_sales_data.csv](https://drive.google.com/your-link-here) → `data/synthetic_beverage_sales_data.csv`

⚠️ **Note:** These files are excluded from version control via `.gitignore`.

---

## 🚀 Getting Started
### 1️⃣ Clone Repository
```
git clone https://github.com/your-username/beverage-sales-analytics.git
cd beverage-sales-analytics
```

### 2️⃣ Install Dependencies
```
pip install -r requirements.txt
```

### 3️⃣ Run Notebooks
Open Jupyter Lab/Notebook and explore the analysis:

```
jupyter notebook notebooks/01_EDA.ipynb
```

📊 Power BI Dashboard

Download the .pbix file from /dashboard

Open with Power BI Desktop

Example Screenshots:
🛠️ Tech Stack

Python: Pandas, Prophet, Matplotlib, Scikit-learn

BI Tool: Power BI

Version Control: Git + GitHub

📌 Future Work

Integrate dashboard into a React/Flask web app

Real-time analytics with streaming data

Deploy ML models with FastAPI/Streamlit
