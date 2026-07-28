# Armando Gonzalez 👋

**AI/ML Engineer in Miami.** M.S. in Data Science and Artificial Intelligence, Florida International
University. Previously a software engineer at a fintech company.

## What I am working on

- **Applied data science:** predicting which recently discharged Medicare patients a primary care
  team should call first. Under Medicare, an avoidable emergency visit comes out of the practice's
  own fixed annual budget, so identifying the patients at risk is both better care and lower cost.
  Gradient boosting with SHAP attribution, so a clinician can see the reason behind every flag.
- **AI and ML engineering:** transformer fine-tuning, and agent systems that watch live services,
  diagnose incidents and recommend actions rather than only answering questions.
- **Data engineering:** medallion lakehouses with dbt and DuckDB, dimensional warehouse and
  data-mart modelling for executive KPI reporting, OLAP cubes, and event streaming with Kafka and
  Redpanda.

## Main projects

| Project | Stack | What it showed |
|---|---|---|
| [Medicare 30-day readmission](https://github.com/armandogon94/Medicare-Readmission-Prediction-Data-Science-Capstone-FIU) | XGBoost, LightGBM, CatBoost, SHAP | Flags readmission risk **0.110 AUROC better than LACE**, the index hospitals use today, so discharge teams can reach the patients who actually need follow-up |
| [Fintech ML system](https://github.com/armandogon94/Portfolio-ML-System) | scikit-learn, MLflow, FastAPI | Catches fraud at **0.857 PR-AUC** where the positive class is 0.17% of traffic, and predicts churn at 0.974, both served behind an API |
| [Multi-industry data platform](https://github.com/armandogon94/Portfolio-Data-Platform) | Postgres, dbt, Prefect, star schema | One warehouse serving several industries, where **a clinic director and a front-desk assistant open the same system and see different KPIs**, because the role decides the metrics and the data they are allowed to reach |
| [Multi-agent business workflows](https://github.com/armandogon94/Portfolio-AI-Agents) | CrewAI, FastAPI, SSE, React Flow | Eight agent crews streaming per-agent state to a live dashboard, and the published finding that **the zero-cost demo was never running a crew at all**, because the tests called the fake model directly instead of through the framework |
| [Finance Tracker](https://github.com/armandogon94/Finance-Tracker) | FastAPI, Postgres, SwiftUI, Tesseract | Receipt photo to reviewable ledger across a web app, a native iOS app and a Telegram bot, with the **offline OCR baseline published at 4/6 totals extracted** rather than quoting a vendor's accuracy claim |

## Skills

- **Programming:** Python · SQL · Java · Bash · C · NoSQL
- **ML and AI:** PyTorch · scikit-learn · XGBoost · LightGBM · CatBoost · SHAP · TensorFlow · Keras · PyTorch Geometric
- **LLM:** LLM APIs · prompt engineering · RAG · AI agents · Hugging Face fine-tuning · anomaly detection
- **Data:** data warehousing · ETL · OLAP · dbt · DuckDB · Parquet · Pentaho · Kafka · Redpanda · Prefect
- **Databases:** PostgreSQL · MongoDB · Redis · Hadoop
- **Frameworks:** Spring Boot · Django · FastAPI · Streamlit
- **Architecture:** event driven · microservices · distributed systems · hexagonal architecture · domain driven design
- **Engineering:** Docker · Git · CI/CD · unit testing · REST APIs
- **Languages:** Spanish (native) · English (fluent)

## What I want to build next

- **Agentic systems that hold state.** Harnesses where an agent runs for hours against a real
  codebase or a live service, keeps a working memory, and is judged on what it finished rather than
  on what it said.
- **Computer vision on real hardware.** Perception where latency and failure modes matter, closer to
  robotics and autonomy than to benchmark leaderboards.
- **Big data at cluster scale.** Taking the warehouse and lakehouse work beyond a single machine,
  into distributed processing where partitioning and shuffle cost drive the design.

Open to **agentic AI**, **ML engineering**, **data engineering** and **data science** roles.

`armandogon94@gmail.com` · [linkedin.com/in/armando-ai](https://linkedin.com/in/armando-ai)
