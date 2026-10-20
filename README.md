# Hi, I'm Kush Agrawal 👋

**AI & Data Engineer in training - building LLM applications, production-grade data pipelines and backend services with Python, PostgreSQL, Kafka, PySpark, Airflow and AWS.**

BSc Computer Science student at the University of West London (graduating 2027), based in London, UK.

📫 [LinkedIn](https://www.linkedin.com/in/kush-agrawalcse/) · kushagra7067@gmail.com

---

## 🔧 What I work with

**Languages:** Python, SQL, Bash, Java
**AI & LLM:** RAG, hybrid search (pgvector + full-text, Reciprocal Rank Fusion), OpenAI API, LangChain, LangGraph, embeddings, LLM evaluation
**Data Engineering:** Kafka, Spark (PySpark, Structured Streaming), Airflow, Cassandra, PostgreSQL, Snowflake
**Backend:** FastAPI, SQLAlchemy (async), REST API design, JWT auth
**Cloud & DevOps:** AWS (Lambda, S3, Kinesis, Glue), Docker, Kubernetes, GitHub Actions CI/CD, Render, Neon
**Testing:** pytest, Testcontainers, Great Expectations, TDD

---

## 🚀 Featured projects

### [contract-review](https://github.com/KushAgrawal1/contract-review) - [Live demo](https://contract-review-aql7.onrender.com)
Contract Review Assistant on the CUAD dataset (510 contracts, 41 clause types). Runs 40 clause checks per contract and returns each answer with a verbatim quote that is verified against the contract text. Hybrid retrieval (pgvector + Postgres full-text, fused with RRF) over 66,561 chunks, built with OpenAI, LangChain, LangGraph, FastAPI and Postgres. **81.8% F1 on 100 held-out contracts at $0.0095 per contract.** Deployed on Render + Neon.

### [Real-Time-Ingestion-Fabric](https://github.com/KushAgrawal1/Real-Time-Ingestion-Fabric)
Real-time medallion ETL over live TfL Underground arrivals - Kafka to Spark Structured Streaming to Cassandra. Streams 4,200+ records per 30-second poll across 11 lines; watermarked deduplication removes 45% duplicates at the silver layer.

### [ledger](https://github.com/KushAgrawal1/ledger)
Async double-entry ledger REST API - FastAPI, PostgreSQL, Kafka. Deadlock-safe idempotent transfers, JWT auth with RBAC, 93% test coverage across 48 tests, CI/CD via GitHub Actions.

### [payment-data-platform](https://github.com/KushAgrawal1/payment-data-platform)
Payment data platform with real-time Kafka ingestion, PySpark batch and stream processing via Medallion architecture, Airflow orchestration, and a PostgreSQL serving layer.

### [retail_airflow](https://github.com/KushAgrawal1/retail_airflow)
End-to-end ELT pipeline for retail sales data - Airflow TaskFlow API, Docker, AWS S3 and Glue.

---

## 🎯 Currently

- Improving answer and citation quality in the Contract Review Assistant
- Working towards AWS Cloud Practitioner certification
- Deepening Spark internals and stream processing patterns
- Open to AI and data engineering internships, placements and graduate roles in London
