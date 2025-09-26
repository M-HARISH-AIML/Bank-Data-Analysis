# Bank Analysis Project

📊 A complete end-to-end banking data analysis project using **MYSQL**, **Power BI**, and **Python** for exploration and validation. This repo demonstrates data ingestion, transformation, exploratory data analysis, KPI creation, and interactive dashboards.

🔎 Project overview
This project analyzes customer and transaction data to produce actionable insights such as customer segmentation, transaction trends, branch performance, product uptake, and churn. It includes:
- SQL scripts for DB creation and analysis (MySQL dialect).
- A Power BI report (`Bank Analysis.pbix`) with interactive dashboards.
- A raw dataset (`Banking.csv`) and Python notebooks for EDA & data cleaning.
- Data dictionary, ER model, test suite, and CI configuration.

📁 Folder structure
bank-analysis/
├─ data/
│  └─ Banking.csv
├─ sql/
│  └─ Bank analysis sql.sql
├─ powerbi/
│  └─ Bank Analysis.pbix
└─ README.md


⚙️ Prerequisites
- MySQL / MariaDB (or adapt SQL for Postgres)
- Power BI Desktop (for `.pbix`)
- Python 3.9+ with: `pandas`, `sqlalchemy`, `mysql-connector-python`, `pytest`, `matplotlib`
- (Optional) GitHub Actions for CI

Install Python dependencies:
```bash
pip install -r requirements.txt
