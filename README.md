# Hi, I'm Lokesh K V 👋
**Data Engineer | GCP · BigQuery · Python · SQL · dbt · RAG · GenAI · RAG**

Data Engineer with hands-on experience building end-to-end pipelines,
scalable data models, and analytics-ready transformations on Google Cloud
Platform. I work across the full data chain — from raw ingestion and
transformation through to business-ready insights — with a strong focus
on data quality, pipeline reliability, and cost efficiency.

---

## 🧠 Engineering Focus
I build systems that are:
- ✔ incremental & idempotent
- ✔ deduplicated and reliable
- ✔ partitioned and cost-efficient
- ✔ reproducible across environments
- ✔ observable and production-grade

---

## 🧰 Tools & Technologies

**Cloud Platform**
- ☁️ Google Cloud Platform
- 🏗️ BigQuery — data warehouse, partitioning, clustering
- 🪣 Cloud Storage (GCS) — raw & staging data lake
- ⚡ Cloud Functions — event-driven pipeline triggers
- 🕐 Scheduled Queries — lightweight pipeline automation

**Transformation & Modeling**
- 🔁 dbt Core — incremental models, MERGE strategy, star schema
- 📊 Dataform — SQL workflow orchestration on BigQuery
- 🐍 Python — ETL, data processing, pipeline scripting
- 🧮 SQL (Analytical SQL) — window functions, CTEs, optimization

**Orchestration**
- 🌬️ Apache Airflow (Astro) — workflow orchestration
- 🔀 GitLab CI/CD — multi-environment pipeline promotion

**GenAI & RAG**
- 🤖 LangChain — chains, prompts, memory, agents
- 🧠 RAG (Retrieval-Augmented Generation) — end-to-end pipeline design
- 🗄️ ChromaDB — vector storage, metadata filtering, similarity search
- 🔢 Vector Embeddings — OpenAI, HuggingFace, proprietary vs open source
- ✍️ Prompt Engineering — query augmentation, hallucination prevention

**Domain Expertise**
- 🚗 Automotive Procurement Analytics (BOM, Delta BOM, ECR, CCM, Claims)
- 🚕 Urban Transportation Analytics (Chicago taxi trip data)
- 📡 IoT Metrics Processing (device performance, uptime, telemetry)

---

## 🚀 Featured Projects

### 🔹 Tesla Financial Intelligence System
Production-grade RAG application on 7 years of Tesla 10-K filings (2017–2024):
- 📄 **Ingestion** → 7 years of Tesla 10-K filings parsed and chunked
- 🔢 **Embeddings** → 17,901 vectors stored in ChromaDB with metadata tagging by year and document section
- 🔍 **Retrieval** → Dynamic Top-K retrieval with metadata filtering for year and section-aware search
- ✍️ **Query Augmentation** → Rewrites vague user questions before retrieval for better context match
- 🛡️ **Hallucination Prevention** → Prompt grounding ensures answers are strictly derived from retrieved context
- 🖥️ **UI** → Streamlit interface deployed and publicly accessible
- 🔗 [GitHub](https://github.com/Lokesh-spec/Tesla-Financial-Intelligence-System)

### 🔹 Urban Transportation Analytics
Production-grade ELT pipeline on GCP ingesting Chicago taxi trip data:
- ☁️ **Ingestion** → GCS → BigQuery raw layer
- 🔁 **Modeling** → dbt incremental model with star schema (fact + dimension tables)
- 🧹 **Deduplication** → MERGE strategy with ROW_NUMBER CTE and 7-day lookback watermark
- 🏗️ **Optimization** → BigQuery partitioning, clustering, and require_partition_filter=True
- 🔀 **CI/CD** → Two-repo GitLab setup across dev, staging, and prod environments

---

## 💼 Professional Work

### 🏢 Tata Consultancy Services — Data Engineer (Oct 2023 – Present)
Building automotive procurement analytics pipelines on GCP:
- 🔩 Delta BOM analysis across multiple vehicle programs
- 📋 Supplier claims automation — reduced manual effort by 70%+
- 📈 2Y/5Y cost benchmarking frameworks
- 🚘 Real-world average car cost estimation models

### 🏢 Bigtec Private Limited — Python ETL Developer (Oct 2020 – Sep 2023)
- 🔄 Built Python ETL workflows moving structured data MySQL → MongoDB
- 📡 Built IoT metrics transformation layer using Python & Pandas (device performance, uptime, operational telemetry)
- 🧹 Data cleaning, normalization, and transformation pipelines

---

## 📚 Currently Growing In
- 🤖 Advanced RAG — query augmentation, re-ranking, hybrid search, agentic RAG
- 🧠 Generative AI — LLM evaluation, observability (LangSmith), prompt optimization
- 🏛️ System design for large-scale data platforms
- 🧪 dbt macros, testing, and documentation
- 📐 Advanced data modeling (SCD Type 2, snapshots)

---

## 💬 Let's Connect
Always open to discussing data engineering architecture,
scalable pipeline design, GenAI applications, and new opportunities 🚀

📧 kvlokesh18@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/lokesh-k-v-2130791a8/)
