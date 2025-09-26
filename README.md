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
│  ├─ Banking.csv
│  └─ README_DATA.md
├─ sql/
│  ├─ Bank analysis sql.sql
│  ├─ schema_create.sql
│  └─ sample_queries.sql
├─ notebooks/
│  └─ eda_bank_analysis.ipynb  (or eda_bank_analysis.py)
├─ powerbi/
│  └─ Bank Analysis.pbix
├─ docs/
│  ├─ data_dictionary.md
│  ├─ ER_diagram.md
│  └─ dashboard_spec.md
├─ tests/
│  └─ test_data_quality.py
├─ .github/
│  ├─ workflows/
│  │  └─ python-ci.yml
│  ├─ ISSUE_TEMPLATE.md
│  └─ PULL_REQUEST_TEMPLATE.md
├─ .gitignore
├─ README.md
├─ CONTRIBUTING.md
├─ LICENSE (MIT)
└─ requirements.txt

⚙️ Prerequisites
- MySQL / MariaDB (or adapt SQL for Postgres)
- Power BI Desktop (for `.pbix`)
- Python 3.9+ with: `pandas`, `sqlalchemy`, `mysql-connector-python`, `pytest`, `matplotlib`
- (Optional) GitHub Actions for CI

Install Python dependencies:
```bash
pip install -r requirements.txt
