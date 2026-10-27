# Shamika Karnik

**AI Engineer: production RAG, agentic LLM systems, and the data pipelines underneath them.**

I build GenAI systems that are evaluated, traced, and deployed: hybrid-retrieval RAG with regression evals, LangChain agents that query real databases, and fine-tuned models measured against their base. Before that, I spent two years at Bank of America building PySpark and Databricks pipelines for regulatory reporting, so data quality, auditability, and scale come first in everything I ship.

**Currently:** AI Engineer at Indiana University's Kelley School of Business · MS Data Science, IU Bloomington (May 2026) · Open to AI Engineer, Applied ML, and GenAI roles

## Featured projects

**[GL Regulatory Reporting System]#([PLACEHOLDER: repo URL])**
RAG over GAAP standards that grounds Claude-generated MD&A commentary, with report generation automated across 50K GL entries. Deployed on AWS EKS with CI/CD and LangSmith tracing.
`LangChain` `Claude` `Qdrant` `Celery` `Redis` `AWS EKS`

**[Conversational SQL Analytics Assistant]#([PLACEHOLDER: repo URL])**
A LangChain SQL agent that turns plain-English questions into multi-step queries over 590K financial records, using Pinecone schema retrieval. Served on GCP.
`LangChain` `Claude` `Pinecone` `PostgreSQL` `FastAPI` `GCP`

**[FitRx: Fine-Tuned AI Fitness Coach]#([PLACEHOLDER: repo URL])**
Gemini 2.5 Flash fine-tuned on 500 curated examples, scoring +6.9% over the base model on LLM-as-judge evaluation. Includes a tool-calling agent on Cloud Run with drift monitoring.
`Gemini` `Vertex AI` `LangChain` `pgvector` `BigQuery`

**[Real-Time Payment Anomaly Detection](https://github.com/shamika2504/payment-anomaly-detection)**
A streaming fraud-scoring pipeline that reached 94% recall and 0.80 F1 on a held-out synthetic evaluation set. Experiments are tracked in MLflow and results surface on a live React dashboard.
`Kafka` `XGBoost` `MLflow` `PostgreSQL` `FastAPI` `React`

## Experience

- **AI Engineer, IU Kelley (2026–present):** Turned 9 TB of raw OmniSOC network logs into validated Parquet. Built RAG over MITRE ATT&CK on Qdrant with analyst-validated regression evals, and a LangChain agentic SOC copilot over TimescaleDB.
- **Software Engineer, Bank of America (2022–2024):** Built PySpark/SQL pipelines over 1M transactions per cycle, cutting manual prep from 2 days to under 20 minutes. Built Databricks ETL across 5 regulatory processes and cut report generation time by 12%.

## Stack

**GenAI & Retrieval:** LangChain · Claude · Gemini · Vertex AI · RAG · fine-tuning · Qdrant · Pinecone · pgvector · LangSmith
**ML:** scikit-learn · XGBoost · Random Forest · model evaluation · feature engineering
**Data & Backend:** Python · SQL · PySpark · Databricks · Kafka · PostgreSQL · BigQuery · Snowflake · FastAPI · Celery · Redis
**Cloud & MLOps:** AWS (EKS, ECR, S3) · GCP · Docker · Kubernetes · GitHub Actions · MLflow · Prometheus

## Contact

[LinkedIn](https://www.linkedin.com/in/shamika-karnik2504) · [Email](mailto:karnik.shamika@gmail.com)
