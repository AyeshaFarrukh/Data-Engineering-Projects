# 🚦 ETL Airflow Traffic Data Pipeline  

## 🧩 Problem Statement  
National highways experience growing congestion due to fragmented toll data systems; each operator maintains traffic records in different file formats (CSV, TSV, and fixed-width text).  
As a Data Engineer, the goal is to design an **automated ETL pipeline using Apache Airflow** that:  
- Extracts data from multiple file formats  
- Transforms and consolidates the datasets into a unified structure  
- Loads the cleaned output into a staging area for analytics  

This project demonstrates building a **production-ready ETL workflow** using **BashOperator** in Apache Airflow to orchestrate all extraction, transformation, and loading steps.  

---

## ⚙️ Tech Stack  
- **Apache Airflow** (DAG orchestration)  
- **BashOperator** (task automation)  
- **Python 3 & Shell scripting**  
- **CSV / TSV / Fixed-Width File Processing**  

---

## 📂 Project Structure  

```text
ETL-Airflow-Traffic-Data-Pipeline/
├── dags/
│   └── etl_toll_data_dag.py         # Airflow DAG definition
├── data/
│   ├── vehicle-data.csv
│   ├── tollplaza-data.tsv
│   ├── payment-data.txt
│   └── final_staging.csv
├── screenshots/
│   ├── task1.1_dag_arguments.png
│   ├── task2.4_fixedwidth_extract.png
│   ├── task2.7_pipeline_definition.png
│   └── task3.4_dag_monitor.png
└── README.md
