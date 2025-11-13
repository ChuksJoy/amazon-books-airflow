#  Amazon Books ETL Pipeline with Apache Airflow

![Apache Airflow](https://img.shields.io/badge/-Apache%20Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![ETL Pipeline](https://img.shields.io/badge/-ETL%20Pipeline-ffcc00?style=flat&logo=data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjMDAwMDAwIiBoZWlnaHQ9IjE2IiB2aWV3Qm94PSIwIDAgMTYgMTYiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48cGF0aCBkPSJNNSAxMmEyIDIgMCAxIDEgNCAwIDIgMiAwIDAgMS00IDB6bTAtOGEyIDIgMCAxIDEgNCAwIDIgMiAwIDAgMS00IDB6bTQgMmExIDEgMCAxIDEgMiAwIDEgMSAwIDAgMS0yIDB6Ii8+PC9zdmc+)

---

##  Project Overview

This project is a **hands-on data engineering exercise** where I built an **ETL pipeline** using **Apache Airflow**, **PostgreSQL**, and **Python** to extract, transform, and load Amazon books data.

>  *This project was inspired by a YouTube tutorial by Sunjana in Data.*  
> Watch it here: [Build a Data Pipeline with Apache Airflow](https://www.youtube.com/watch?v=3xyoM28B40Y)

The goal was to understand how to orchestrate data workflows with Airflow and integrate different tools in a practical project setup.

---

## ⚙️ Tools & Technologies

| Category | Tools Used |
|-----------|-------------|
| **Orchestration** | Apache Airflow |
| **Database** | PostgreSQL |
| **Programming** | Python |
| **ETL Logic** | Airflow Operators, Python Scripts |
| **Environment** | Virtual Environment (venv) |
| **Version Control** | Git & GitHub |

---

##  Pipeline Architecture

1. **Extract** – Load raw data (CSV/JSON) from source.
2. **Transform** – Clean, parse, and structure the dataset using Python operators.
3. **Load** – Write the transformed data into a PostgreSQL database.
4. **Orchestrate** – Automate all steps using Airflow DAGs and task dependencies.


