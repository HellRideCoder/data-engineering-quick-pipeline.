# data-engineering-quick-pipeline
Automated ETL pipeline with Airflow, Spark &amp; PostgreSQL
# Data Engineering Quick Win Pipeline 🚀

A lightweight ETL (Extract‑Transform‑Load) pipeline that ingests order data (CSV/JSON), cleans & deduplicates it with PySpark, and loads it into PostgreSQL—fully automated on a daily schedule via Apache Airflow.

---

## 🔧 Features

- **Ingestion**: Read raw orders from `data/orders.csv`  
- **Cleaning**: Remove duplicates & standardize formats using PySpark  
- **Orchestration**: Schedule daily runs with Apache Airflow DAG  
- **Load**: Write cleaned data into a PostgreSQL `orders` table  
- **Sample Data**: Included `orders.csv` for quick testing  
- **Documentation**: Clear setup & usage instructions

---

## 📦 Getting Started

1. **Clone** this repo  
   ```bash
   git clone https://github.com/<your‑user>/data-engineering-quick-pipeline.git
   cd data-engineering-quick-pipeline
   Add initial README
