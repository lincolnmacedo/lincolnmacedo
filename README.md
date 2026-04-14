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
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat&logo=visualstudiocode&logoColor=white)

---

## What I build

```
Raw sources  →  Ingestion  →  Transform  →  Serving  →  Dashboards
               (Python)       (dbt/SQL)    (BigQuery)   (Power BI / Looker)
                  ↕               ↕             ↕
              Cloud Storage   Data vault    Data marts
              (GCS / S3)    (staging/int)  (analytics)
```

- **Data pipelines** — production ETL/ELT with retry logic, error handling, structured logging
- **Data modeling** — dbt projects with staging → intermediate → mart layer pattern
- **Cloud infra** — GCP/AWS environments managed with Terraform, dev/prod separation
- **Web scraping** — scalable scrapers (Selenium + BeautifulSoup) with BigQuery sinks
- **Automation** — Google Sheets + Apps Script + API integrations
- **BI & delivery** — optimized SQL, partitioned/clustered BigQuery tables, dashboard-ready marts

---

## Featured projects

> All repositories follow a consistent structure: `environments/dev` + `environments/prod`, CI/CD via GitHub Actions, and modular `src/` layout.

| Repository | Description | Stack |
|---|---|---|
| [infra-platform-gcp](https://github.com/lincolnmacedo/infra-platform-gcp) | Production data platform: BigQuery, GCS, Cloud Functions, IAM, dev/prod via Terraform | GCP · Terraform · BigQuery |
| [transform-models-dbt](https://github.com/lincolnmacedo/transform-models-dbt) | dbt project with staging, intermediate, mart layers. Tests, docs, CI/CD on BigQuery | dbt · BigQuery · SQL |
| [ingestion-pipeline-python](https://github.com/lincolnmacedo/ingestion-pipeline-python) | Scalable ETL/ELT pipelines: REST APIs → BigQuery, retry logic, structured logging | Python · BigQuery · Airflow |
| [ingestion-scraper-python](https://github.com/lincolnmacedo/ingestion-scraper-python) | Production web scraping: Selenium + BeautifulSoup, proxy rotation, dedup, BQ sink | Python · Selenium · BigQuery |
| [analytics-dashboard-bq](https://github.com/lincolnmacedo/analytics-dashboard-bq) | BigQuery optimization patterns: partitioning, clustering, cost-efficient queries, marts | SQL · BigQuery · Power BI |
| [serving-automation-sheets](https://github.com/lincolnmacedo/serving-automation-sheets) | Google Sheets + Apps Script automation: API integrations, scheduled triggers, prod patterns | Apps Script · APIs · GSheets |

---

## Repository conventions

Every project in this profile follows the same conventions to demonstrate **data governance and engineering best practices**:

```
{layer}-{domain}-{stack}/
├── .github/
│   └── workflows/
│       ├── ci.yml          # lint, test, validate on PR
│       └── cd.yml          # deploy dev → prod on merge
├── environments/
│   ├── dev/config.yml      # dev variables, small samples
│   └── prod/config.yml     # prod variables, monitoring, alerts
├── src/
│   ├── ingestion/
│   ├── transform/
│   └── utils/
├── tests/
│   ├── unit/
│   └── integration/
├── docs/
│   └── architecture.md
├── .env.example
├── Makefile                # make dev / make test / make deploy
├── pyproject.toml
└── README.md
```

**Naming convention:** `{layer}-{domain}-{stack}`  
Layers: `ingestion` · `transform` · `serving` · `infra` · `analytics`

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
