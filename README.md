# 🏥 Pulse Corp Data Engineering Case Study

## 📌 Overview

This case study presents a scalable, resilient, and automated data architecture designed to solve real-world data challenges faced by Pulse Corp—a hypothetical pharmaceutical organization. The focus is on building robust pipelines, ensuring data quality, handling schema evolution, and enabling real-time analytics using modern data engineering practices.

---

## 👨‍💻 Author

**Nitesh Ranjan Singh**  
Data Engineer | Azure | PySpark | Delta Lake | Power BI  
[LinkedIn](https://www.linkedin.com/in/nitesh0007/) • [Email](mailto:niteshranjansingh85389@gmail.com)

---

## 🛠️ Tech Stack

- **Cloud & Orchestration**: Azure Data Factory, Azure Databricks, Azure Monitor
- **Processing & Storage**: PySpark, Delta Lake, Azure Data Lake Storage Gen2
- **Monitoring & Observability**: Azure Log Analytics
- **Analytics**: Power BI
- **Development Practices**: CI/CD-ready, schema evolution support, modular pipeline design

---

## 🏗️ Solution Architecture

The data platform follows the **Medallion Architecture**:
- **Bronze Layer**: Raw data ingestion via ADF + Databricks Auto Loader
- **Silver Layer**: Cleansed data with DQ validation using PySpark
- **Gold Layer**: Curated datamarts for Power BI dashboards and reporting

Key Features:
- Real-time ingestion with auto schema evolution
- End-to-end data quality framework with alerting and auditability
- SCD Type-2 dimension modeling for historical accuracy
- Fact tables that enable YTD/LTD metrics and trend analytics

---

## 📊 Business Impact

- ✅ Real-time dashboards for operational users
- ✅ Daily reports with high integrity for business stakeholders
- ✅ 0-click automation and full pipeline observability
- ✅ Future-proof design handling changing schemas effortlessly

---

## 📁 Repository Structure
📦pulsecorp-case-study/
├── 📁 assets/
│ └── architecture_diagram.png # Visual architecture diagram (optional)
├── 📁 notebooks/
│ ├── dq_checks.ipynb # PySpark code for data quality
│ ├── ingestion_pipeline.ipynb # Ingestion logic using ADF + Auto Loader
│ └── dimensional_modeling.ipynb # SCD2 logic and datamart construction
├── 📁 datasets/
│ ├── product.csv # Sample input data
│ ├── sales.csv
│ └── inventory.csv
├── 📁 reports/
│ └── PulseCorp_CaseStudy_Presentation.pdf # Converted PDF of final presentation
├── README.md
└── LICENSE (optional)

---

## 🔍 Sample Use Cases Solved

- "What’s the current stock of Product X in Warehouse Y?"
- "What are LTD vs YTD revenue trends per product?"
- "How much revenue did Category A generate this year?"

---

## 🧠 Key Learnings

This case study showcases:
- Medallion architecture implementation in Azure
- Hands-on application of PySpark and Delta Lake for scalable processing
- Real-world problem solving for schema evolution, data quality, and auditability
- Dimensional modeling using SCD2 for historical traceability

---

## 📞 Contact

If you're a recruiter or hiring manager and would like to know more, feel free to connect!

📧 niteshranjansingh99@gmail.com  
🌐 [LinkedIn](https://linkedin.com/in/nitesh-ranjan-singh)

---
