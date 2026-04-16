<div align="center">

# Lincoln Macedo

**Data Engineer · Analytics Engineer · 5+ years**

*Engineering Data. Enabling Decisions.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/lincolnmacedo)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/lincolnmacedo)

</div>

---

## About me

Data Engineer with 5+ years designing and building **end-to-end data platforms** — from raw ingestion to production-ready dashboards. I work across the full data stack: scalable ETL/ELT pipelines, cloud data warehousing, data modeling, and BI delivery.

I focus on **automation over manual work**, **scalable architectures**, and **production-ready code**. Every system I build is designed to run reliably at scale, with proper governance, environment separation (dev/prod), and observability built in from day one.

---

## Tech stack

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

### Data platforms & warehouses
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat&logo=googlebigquery&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat&logo=snowflake&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)

### Cloud
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)

### BI & analytics
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Looker](https://img.shields.io/badge/Looker-4285F4?style=flat&logo=looker&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![GA4](https://img.shields.io/badge/GA4-E37400?style=flat&logo=googleanalytics&logoColor=white)

### Dev tools
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat&logo=visualstudiocode&logoColor=white)

---

## What I build

```
[Sources]  →  ingestion  →  transform  →  serving  →  Consumers
              (Python /      (dbt /        (FastAPI /   (BI / APIs)
               Snowpark /     PySpark /     Cloud Run /
               Lambda)        SparkSQL)     Kubernetes)
                  ↕               ↕              ↕
            GCS / S3        BQ / Snowflake  REST APIs
            Raw layer       Staging → Mart  Dashboards

[Events]   →  streaming  →  Delta / BigQuery
              (Kafka +
               PySpark)

[Infra]    →  Terraform  →  GCP · AWS · Snowflake · Databricks
```

- **Data pipelines** — production ETL/ELT with retry logic, error handling, structured logging
- **Data modeling** — dbt projects with staging → intermediate → mart layer pattern
- **Medallion architecture** — bronze → silver → gold on Databricks with Delta Lake
- **Cloud infra** — GCP and AWS environments managed with Terraform, dev/prod separation
- **Real-time streaming** — Kafka + PySpark Structured Streaming with watermarking
- **Data serving** — FastAPI over BigQuery mart tables, deployed on Cloud Run and Kubernetes
- **Orchestration** — Airflow DAGs coordinating cross-platform pipelines

---

## Featured projects

> Repositories follow `{layer}-{platform}-{domain}` naming with dev/prod separation, CI/CD via GitHub Actions, and semantic versioning on every release.

| Repository | Description | Stack |
|---|---|---|
| [infra-gcp](https://github.com/lincolnmacedo/infra-gcp) | GCP data platform: BigQuery, GCS, Cloud Run, IAM — dev/prod via Terraform | GCP · Terraform |
| [ingestion-bigquery-ecommerce](https://github.com/lincolnmacedo/ingestion-bigquery-ecommerce) | Python ETL: Olist CSV + API → BigQuery raw tables, retry logic, structured logging | Python · BigQuery |
| [transform-bigquery-ecommerce](https://github.com/lincolnmacedo/transform-bigquery-ecommerce) | dbt on BigQuery: staging → intermediate → mart, tests, docs, slim CI | dbt · SQL · BigQuery |
| [transform-databricks-logistics](https://github.com/lincolnmacedo/transform-databricks-logistics) | Medallion architecture on Databricks: bronze → silver → gold with Delta Lake | PySpark · Databricks |
| [infra-snowflake](https://github.com/lincolnmacedo/infra-snowflake) | Snowflake infrastructure: databases, warehouses, RBAC roles — Terraform managed | Snowflake · Terraform |
| [orchestration-airflow](https://github.com/lincolnmacedo/orchestration-airflow) | Airflow DAGs orchestrating all platform pipelines across GCP, AWS, Databricks | Airflow · Python |

---

## GitHub stats

<div align="center">

<!-- OPTION A: After deploying your own Vercel instance (recommended — replace YOUR_VERCEL_URL) -->
<!-- ![Lincoln's GitHub stats](https://YOUR_VERCEL_URL/api?username=lincolnmacedo&show_icons=true&theme=default&hide_border=true&count_private=true&include_all_commits=true) -->
<!-- ![Top Languages](https://YOUR_VERCEL_URL/api/top-langs/?username=lincolnmacedo&layout=compact&theme=default&hide_border=true&langs_count=8) -->

<!-- OPTION B: Active now — swap for OPTION A once Vercel is deployed -->
![GitHub Streak](https://streak-stats.demolab.com/?user=lincolnmacedo&theme=default&hide_border=true)

</div>

---

<div align="center">

*"Build systems, not tasks."*

[![LinkedIn](https://img.shields.io/badge/Let's%20connect-LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/lincolnmacedo)

</div>
