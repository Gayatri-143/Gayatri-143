<div align="center">

# Gayatri Jadhav

**Data Engineering Developer | Computer Science Student | Open to Opportunities**

<br />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00D2FF&center=true&vCenter=true&width=700&lines=Data+Engineer+Developer;PySpark+%7C+Databricks+%7C+AWS;Building+Scalable+ETL%2FELT+Pipelines;Transforming+Raw+Data+into+Analytics-Ready+Gold)](https://git.io/typing-svg)

</div>

---

##  About Me

```yaml
Name: Gayatri Jadhav
Role: Data Engineer Developer (Computer Science Student)
Focus: Scalable ETL/ELT Pipelines & Distributed Data Processing
Currently Working On:
  - Retail ETL Pipeline (Databricks & PySpark - Medallion Architecture)
  - Cloud-Native Data Infrastructure & AWS
  - Production Data Engineering Fundamentals & Advanced SQL
```
---

##  Featured Data Engineering Project

### 🛒 [Retail ETL Pipeline — Medallion Architecture](https://github.com/Gayatri-143/retail-etl-pipeline)

A production-style ETL data pipeline engineered on **Databricks** using **Apache Spark (PySpark)** to process raw retail transactions into analytics-ready datasets.

####  Architecture & Data Flow

```
┌─────────────────┐       ┌─────────────────────────────────────────────────────────────┐
│  Raw Data Source │ ────► │                     MEDALLION ARCHITECTURE                  │
│ (CSV / JSON /   │       │                                                             │
│   Database)     │       │  ┌──────────────┐     ┌──────────────┐     ┌─────────────┐  │
└─────────────────┘       │  │ Bronze Layer │ ──► │ Silver Layer │ ──► │ Gold Layer  │  │
                          │  │  (Raw Ingest)│     │  (Cleaned)   │     │ (Aggregated)│  │
                          │  └──────────────┘     └──────────────┘     └─────────────┘  │
                          └─────────────────────────────────────────────────────────────┘
                                                                                      │
                                                                       ┌──────────────▼──────────────┐
                                                                       │ Analytics & BI Dashboards   │
                                                                       └─────────────────────────────┘
```

####  Technical Highlights & Implementation
- **Bronze Layer (Ingestion):** Ingests raw multi-format transaction logs into Delta/Parquet storage preserving raw audit history.
- **Silver Layer (Transformation & Cleaning):** Enforces schema validation, handles null values, deduplicates customer records, and standardizes timestamps.
- **Gold Layer (Aggregation & Analytics):** Computes business metrics (e.g., daily sales rollups, customer LTV, product performance) optimized for high-performance SQL querying.
- **Tech Stack:** `PySpark` • `Databricks` • `Delta Lake` • `Spark SQL` • `Python` • `ETL Pipeline Design`

---

##  Tech Stack & Tooling

<h3 align="center">Programming Languages</h3>
<p align="center">
  <img src="https://skillicons.dev/icons?i=py,cpp,java,js,ts,go" alt="Languages" />
</p>

<br />

<h3 align="center">Data Engineering & Databases</h3>
<p align="center">
  <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb" alt="Databases" />
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" alt="Apache Spark" />
  <img src="https://img.shields.io/badge/PySpark-EE4C2C?style=for-the-badge&logo=python&logoColor=white" alt="PySpark" />
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white" alt="Databricks" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" />
</p>

<br />

<h3 align="center">Cloud & DevOps</h3>
<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,docker,linux,git,github" alt="Cloud & DevOps" />
</p>

<br />

<h3 align="center">Web & Frameworks</h3>
<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,react,flask" alt="Web & Frameworks" />
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit" />
</p>

<br />

<h3 align="center">Data Science & AI</h3>
<p align="center">
  <img src="https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="Scikit-Learn" />
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge" alt="Matplotlib" />
  <img src="https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge" alt="Seaborn" />
</p>

<br />

<h3 align="center">Tools & Environment</h3>
<p align="center">
  <img src="https://skillicons.dev/icons?i=vscode,anaconda" alt="Tools" />
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter" />
  <img src="https://img.shields.io/badge/n8n-FF6584?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n" />
</p>

---

##  Other Projects

| Project Name | Domain / Focus | Key Technologies | Description |
| :--- | :--- | :--- | :--- |
| **ForensIQ** | Cybersecurity & AI | `Python`, `LLMs`, `Knowledge Graphs`, `SOC Workflows` | AI-powered threat intelligence & cybersecurity investigation assistant. |
| **House Price Prediction** | Machine Learning | `Python`, `Scikit-Learn`, `Pandas`, `ML` | Predictive regression model for real estate pricing estimation. |
| **Air Quality Monitoring System** | Data & Analytics | `Python`, `Streamlit`, `Pandas` | Interactive dashboard analyzing real-time air quality metrics. |
| **Electricity Consumption Forecasting** | Time-Series ML | `Python`, `Scikit-Learn`, `Time-Series` | Time-series forecasting for grid energy consumption optimization. |
| **Weather Application** | Backend Engineering | `Go (Golang)`, `REST API` | High-performance concurrent weather data backend service in Go. |
| **Athlytics** | Mobile Analytics | `Flutter`, `Dart`, `Firebase` | Sports analytics and performance tracking mobile application. |
| **Student Performance Analyzer** | Data Analysis | `Python`, `Pandas`, `Matplotlib` | Exploratory data analysis identifying key academic performance drivers. |
| **Podcast Listening Time Prediction** | Predictive Analytics | `Python`, `Scikit-Learn`, `ML` | ML model estimating user engagement and podcast drop-off rates. |

---

##  Currently Learning & Upskilling

- [ ]  **Advanced PySpark:** Spark optimization, AQE, custom partitioning, & memory tuning.
- [ ]  **Data Warehousing:** Snowflake / Redshift schema patterns, star schema & SCD modeling.
- [ ]  **Workflow Orchestration & Streaming:** Apache Airflow DAG management & Apache Kafka event streaming.
- [ ]  **Cloud Native Data Engineering:** AWS Glue, EMR, S3, and Athena for serverless ETL.
- [ ]  **Advanced SQL:** Window functions, CTEs, query plan optimization, & analytical queries.

---

##  Career Goal

> *"My goal is to evolve into a Data Engineer capable of architecting resilient, production-grade data pipelines that power high-stakes analytics and machine learning applications. I am committed to continuous learning, software engineering rigor, and deep technical domain expertise."*

---

##  Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gayatri-u-jadhav)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jadhavgayatri869@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Gayatri-143)

</div>

---

<div align="center">

 *“Data is the raw material of the digital age — engineering makes it useful.”*

</div>
