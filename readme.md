# Hi, I'm Muhammad Usman Mamoon 👋

## Data Engineering · Cloud · AI/ML

I build data pipelines, backend systems and cloud-based data solutions using **Python, SQL, PostgreSQL and AWS**.

My route into Data Engineering comes from both technology and business. I have spent years using data to operate and grow my own manufacturing business, **Pluto Packaging**, before formalising and expanding that experience through intensive Data Engineering, AI & Machine Learning training.

I’m particularly interested in the point where **data engineering, cloud infrastructure and AI meet** — building reliable systems that collect, transform, validate and serve data for analytics and intelligent applications.

---

# 🧰 Technology Stack

### Programming & Data

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
</p>

**Python · SQL · PostgreSQL · Pandas · ETL · Data Pipelines · Data Modelling · Normalisation · Dimensional Modelling · Star Schema · Data Warehousing · Parquet**

### Cloud & Infrastructure

<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS_Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white" />
  <img src="https://img.shields.io/badge/Amazon_S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white" />
  <img src="https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white" />
</p>

**AWS Lambda · S3 · RDS · EC2 · CloudWatch · IAM · Athena · Glue · Step Functions · EventBridge · SNS · Terraform · Infrastructure as Code**

### Backend & Software Engineering

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
</p>

**FastAPI · REST APIs · JWT · Async/Await · pytest · TDD · Integration Testing · Git · GitHub Actions · CI/CD**

### AI & Machine Learning

**scikit-learn · TF-IDF · Logistic Regression · Decision Trees · Perceptrons · Neural Networks · Transformers · LLMs · RAG · Sentence Transformers · Hugging Face**

---

# 🚀 Featured Projects

## 🏭 Pluto Data Platform — Commercial Data Engineering Project

**Python · Pandas · Excel · Parquet · pytest · ETL · Data Quality**

Building an internal Data Engineering platform for **Pluto Packaging**, a manufacturing business I founded and operate.

The platform is designed to replace fragmented spreadsheet-based reporting with a structured, testable and analytics-ready data pipeline.

### Current Engineering Work

- Profiled **4 operational workbooks containing 61 worksheets**
- Consolidated **27 customer ledgers into 897 standardised transactions**
- Built automated ingestion from inconsistent Excel structures
- Standardised inconsistent transaction schemas and column names
- Created staging and curated data layers
- Added transaction classification for sales, payments, tax, advances and returns
- Implemented data-quality checks for invalid dates, missing dates, negative values and inconsistent ledger records
- Added automated pytest coverage
- Generated CSV and Parquet analytics datasets
- Kept real commercial data isolated from the public repository

### Architecture

```text
Operational Excel Data
        ↓
Python / Pandas Ingestion
        ↓
Raw / Staging Layer
        ↓
Data Validation
        ↓
Transformation & Classification
        ↓
Curated Parquet Data
        ↓
PostgreSQL
        ↓
Analytics Models
        ↓
Power BI
```

The platform is being developed progressively toward **PostgreSQL, automated cloud processing and business intelligence dashboards**.

🔗 **[View Project](https://github.com/jupiter5805/pluto-data-platform)**

---

## ☁️ Automated Cloud Data Pipeline — ToteSys

**Python · SQL · PostgreSQL · AWS Lambda · S3 · EventBridge · CloudWatch · SNS · IAM · Terraform · Parquet · pytest**

Built an automated end-to-end cloud Data Engineering pipeline that extracts operational PostgreSQL data, transforms it and produces analytics-ready datasets using serverless AWS infrastructure.

### Highlights

- Automated ETL
- Incremental ingestion
- PostgreSQL source system
- Dimensional modelling
- Parquet processing
- AWS Lambda
- S3 data storage
- Event-driven execution
- Terraform Infrastructure as Code
- Automated testing
- Monitoring and alerts
- IAM security

🔗 **[View Project & README](https://github.com/jupiter5805/ETL-Team-Project)**

---

## 🤖 AI-Powered SMS Spam Classifier & RAG

**Python · scikit-learn · Pandas · TF-IDF · Logistic Regression · TinyLlama · Sentence Transformers · RAG · PyTorch · pytest · GitHub Actions**

Built an end-to-end NLP application for SMS spam detection.

### Results

- **97.8% classification accuracy**
- **91.3% spam F1 score**
- TF-IDF feature engineering
- Logistic Regression classification
- Confidence scoring
- CLI/chatbot interface
- Batch processing
- Semantic retrieval using Sentence Transformers
- TinyLlama conversational responses
- RAG-based contextual explanations
- Automated testing and CI

🔗 **[View Project](https://github.com/jupiter5805/sms-spam-classifier)**

---

## 🌐 PlusOne Event API

**Python · FastAPI · PostgreSQL · SQL · JWT · bcrypt · pytest · REST APIs**

Built a secure backend API for creating and managing events and RSVPs.

### Highlights

- FastAPI REST architecture
- PostgreSQL relational database
- User registration and authentication
- JWT authorisation
- Event creation and management
- RSVP workflows
- Duplicate RSVP protection
- SQL analytics
- **47 automated integration tests**

🔗 **[View Project](https://github.com/jupiter5805/py-nc-plus-one)**

---

## 🚀 Orion 7 Rover Mission Control

**Python · OOP · TDD · pytest · JSON · Logging · CLI · Custom Exceptions**

Built a layered Python mission-control application for processing and executing rover missions across bounded plateaus.

### Highlights

- Object-oriented architecture
- Multiple rover support
- Command parsing and validation
- Boundary protection
- Mission logging
- JSON mission archives
- Interactive CLI
- Unit and integration testing

🔗 **[View Project](https://github.com/jupiter5805/py-orion-rover-mission)**

---

## 🔄 Mini Sales ETL Pipeline

**Python · CSV · JSON · pytest · ETL**

Built a lightweight end-to-end ETL pipeline to practise the core stages of Data Engineering.

```text
Raw CSV
   ↓
Extract
   ↓
Transform & Clean
   ↓
Aggregate
   ↓
Processed CSV + JSON
```

Includes automated tests for ingestion, transformations and summary calculations.

🔗 **[View Project](https://github.com/jupiter5805/mini-sales-etl)**

---

# 🧠 What I'm Currently Building

My current focus is developing the **Pluto Data Platform** into a complete commercial analytics system covering:

```text
Sales
   │
   ├── Customers
   ├── Orders
   └── Receivables
         │
         ▼
Suppliers ── Purchases ── Payables
         │
         ▼
Inventory ── Fabric ── Production
         │
         ▼
PostgreSQL Analytics Layer
         │
         ▼
Power BI
```

The aim is to connect real manufacturing operations with modern Data Engineering practices including:

- automated ingestion
- relational modelling
- data-quality validation
- dimensional modelling
- orchestration
- monitoring
- cloud infrastructure
- business intelligence

---

# 🎯 Current Areas of Interest

- Data Engineering
- Cloud Data Platforms
- ETL / ELT
- Data Quality & Observability
- Data Warehousing
- Analytics Engineering
- AWS
- AI/ML Data Infrastructure
- Retrieval-Augmented Generation
- Automation

---

# 👨‍💻 Background

Before specialising in Data Engineering, I worked across **Civil Engineering, project delivery, operations, management and entrepreneurship**.

As founder of Pluto Packaging, I have spent years using operational and commercial data to support **pricing, production, customers and business decisions**.

I later formalised and expanded that experience through intensive training in **Data Engineering, cloud infrastructure, software engineering, AI and Machine Learning**.

That combination means I approach technical problems from both sides:

**How should we engineer it?**

and

**What business problem does it actually solve?**

---

# 🌍 Outside Tech

I'm an automotive enthusiast and performance motorcyclist, and have organised car shows and a **Fast & Furious premiere event**.

I also enjoy **Age of Empires II**, story-driven games, anime, strength training, travelling and entrepreneurship.

---

# 📫 Connect

<p>
  <a href="mailto:muhammadusman5805@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>

  <a href="https://github.com/jupiter5805">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

📍 Manchester, United Kingdom
