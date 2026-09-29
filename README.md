<div align="center">
  
![Header](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,14,18,20,24&height=280&section=header&text=Kajol%20Dave&fontSize=70&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Data%20Scientist%20%7C%20ML%20Engineer%20%7C%20Analytics%20Architect&descAlignY=55&descSize=20)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kajol-dave)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Kajoldave173/)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=todoist&logoColor=white)](https://kajoldave173.github.io/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kajoldave031@gmail.com)

</div>

---

## 👋 About Me

Data Scientist with **4+ years of production experience** building end-to-end ML systems that drive measurable business impact. Specialized in **demand forecasting**, **marketing analytics**, and **real-time personalization pipelines** across retail and digital marketing domains. Expert in translating complex data challenges into scalable, production-grade solutions using Python, SQL, PySpark, and Azure cloud infrastructure.

**Current Focus:** Product Analytics at SupplyBistro | MS Business Analytics @ UMass Amherst

**Core Expertise:** Forecasting Models • Marketing Mix Modeling • Real-Time ML Pipelines • Cloud-Native Data Engineering • A/B Testing & Experimentation

---

## 🏗️ System Architecture & Data Flow

```mermaid
graph TB
    subgraph Data Sources
        A1[Ad Platforms<br/>Google Meta CTV]
        A2[Transactional DB<br/>3000+ SKUs]
        A3[Event Streams<br/>5M+ records]
    end
    
    subgraph Ingestion Layer
        B1[Azure Data Factory<br/>ETL Pipelines]
        B2[Event Hubs<br/>Structured Streaming]
    end
    
    subgraph Storage Layer
        C1[(ADLS Gen2<br/>Bronze Layer)]
        C2[(Delta Lake<br/>Silver Layer)]
        C3[(Gold Layer<br/>Feature Store)]
    end
    
    subgraph ML Platform
        D1[Databricks<br/>Spark Pandas UDFs]
        D2[MLflow<br/>Model Registry]
        D3[Feature Store<br/>75+ Features]
    end
    
    subgraph Models
        E1[Demand Forecasting<br/>XGBoost Prophet]
        E2[Marketing Mix Model<br/>Multi-Touch Attribution]
        E3[Recommendation Engine<br/>Behavioral Features]
        E4[CLV Prediction<br/>BG/NBD + ML]
    end
    
    subgraph Serving Layer
        F1[Real-Time API<br/>FastAPI]
        F2[Batch Predictions<br/>Scheduled Jobs]
    end
    
    subgraph Analytics Layer
        G1[Power BI<br/>DirectLake]
        G2[Streamlit<br/>Dashboards]
        G3[Plotly<br/>Interactive Viz]
    end
    
    A1 & A2 & A3 --> B1 & B2
    B1 & B2 --> C1
    C1 --> C2
    C2 --> C3
    C3 --> D1 & D2 & D3
    D1 & D2 & D3 --> E1 & E2 & E3 & E4
    E1 & E2 & E3 & E4 --> F1 & F2
    F1 & F2 --> G1 & G2 & G3
```

---

## 💼 Professional Journey

```mermaid
timeline
    title Career Progression
    section 2020-2021
        Mar 2020 : Data Associate at Mphasis
               : ETL pipelines for Tier-1 bank
               : Docker and Kubernetes migration
    section 2021-2024
        Sep 2021 : Data Scientist at Cybage
               : Demand forecasting 3000+ SKUs
               : Marketing Mix Modeling
               : Real-time recommendation system
    section 2024-2026
        Aug 2024 : MS Business Analytics
               : University of Massachusetts Amherst
        Feb 2026 : DS Intern at Stanley Black Decker
               : Revenue opportunity analysis
               : Forecast accuracy improved 18%
    section 2026-Present
        Sep 2026 : Product Analyst at SupplyBistro
               : Current role
```

---

## 🎯 Technical Expertise

```mermaid
mindmap
  root((Kajol Dave<br/>Data Scientist))
    Machine Learning
      XGBoost
      LightGBM
      Prophet
      Random Forest
      ARIMA
      Neural Networks
    Data Engineering
      PySpark
      Delta Lake
      Medallion Architecture
      Structured Streaming
      ETL and ELT
      Apache Airflow
    Cloud and DevOps
      Azure Databricks
      ADLS Gen2
      Azure Data Factory
      Event Hubs
      Docker
      Kubernetes
      MLflow
      DVC
    Analytics
      Marketing Mix Modeling
      Multi Touch Attribution
      Demand Forecasting
      CLV Modeling
      A/B Testing
      Sequential Testing
      RFM Analysis
      Propensity Modeling
    Visualization
      Power BI
      Tableau
      Streamlit
      Plotly
```

---

## 🛠️ Technology Stack

<div align="center">

### **Programming & Data Science**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apache-spark&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)

### **Machine Learning & MLOps**

![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge&logo=xgboost&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![DVC](https://img.shields.io/badge/DVC-13ADC7?style=for-the-badge&logo=dvc&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)

### **Cloud & Data Engineering**

![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apache-airflow&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-00ADD8?style=for-the-badge&logo=delta&logoColor=white)

### **Analytics & Visualization**

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)

</div>

---

## 📊 Skill Distribution

```mermaid
%%{init: {'theme':'base', 'themeVariables': { 'pie1':'#FF6B6B', 'pie2':'#4ECDC4', 'pie3':'#45B7D1', 'pie4':'#FFA07A', 'pie5':'#98D8C8'}}}%%
pie title Technical Expertise Distribution
    "ML & Forecasting" : 30
    "Data Engineering" : 25
    "Cloud & DevOps" : 20
    "Analytics & BI" : 15
    "Experimentation" : 10
```

---

## 🚀 Featured Projects

### 🎯 [Customer Lifetime Value Engine](https://github.com/Kajoldave173/clv-engine)

**Production-grade CLV prediction system with explainability and drift monitoring**

Built a hybrid probabilistic-ML pipeline combining BG/NBD, Gamma-Gamma, and Optuna-tuned XGBoost on **1M+ e-commerce transactions**, achieving **50% MAE reduction** over baseline (£673 → £334, R² 0.965).

**Key Features:**
- SHAP-powered explainability dashboard with What-If simulator for campaign ROI estimation
- PSI drift monitoring with 94 pytest tests ensuring production reliability
- DVC-versioned artifacts with MLflow tracking for reproducible experiments

**Tech Stack:** `Python` `XGBoost` `SHAP` `Streamlit` `Docker` `MLflow` `DVC` `Optuna`

**Impact:** Enables data-driven customer segmentation and targeted marketing strategies with quantified uncertainty

---

### 🧪 [Online Experimentation Platform](https://github.com/Kajoldave173/experimentation-platform)

**Sequential testing framework demonstrating rigorous A/B test methodology**

Demonstrated that daily A/B test monitoring **inflates false positives from 5% to 25-30%** on 50K+ simulated sessions. Implemented **mSPRT sequential testing** enabling valid anytime checks while maintaining statistical rigor.

**Key Features:**
- Thompson Sampling bandit dynamically routing **85%+ traffic** to winning treatment in real-time
- Interactive Streamlit simulator for hypothesis testing education
- Comprehensive statistical validation using SciPy and statsmodels

**Tech Stack:** `Python` `SciPy` `statsmodels` `NumPy` `Plotly` `Streamlit`

**Impact:** Reduces user exposure to underperforming variants while maintaining statistical validity

---

### 📈 [Surecast: Calibrated Demand Forecasting](https://github.com/Kajoldave173/surecast)

**Day-ahead demand forecaster with conformalized prediction intervals and SHAP explainability**

Built an honest forecasting system on UCI bike-share data featuring **conformalized quantile regression** for calibrated uncertainty estimates. Gradient-boosted model achieves **23% MAE reduction** over seasonal-naive baseline with prediction intervals achieving **87.5% empirical coverage** on held-out data.

**Key Features:**
- Conformalized prediction intervals (not just point forecasts) via CQR
- SHAP explainability for every prediction with interactive dashboard
- Honest rolling-origin backtesting with strict anti-leakage guards
- Automated model card generation from metrics

**Tech Stack:** `Python` `scikit-learn` `SHAP` `Streamlit` `matplotlib`

**Impact:** Quantifies forecast uncertainty in a way decision-makers can trust

---

### 🔍 [InfoHunter: OSINT Intelligence Suite](https://github.com/Kajoldave173/infohunter)

**Modular OSINT automation platform for security intelligence gathering**

Built a comprehensive Open Source Intelligence suite for collecting and analyzing information about users, emails, and domains. Generates professional reports (PDF, JSON) with both interactive and automated workflows.

**Key Features:**
- Username analysis across social networks (Sherlock, Maigret integration)
- Email leak and password checks (HIBP, Holehe, IntelX, EmailRep)
- Domain intelligence (WHOIS, DNS, Shodan, Hunter.io, VirusTotal)
- Streamlit web frontend with .env editor and report management
- Automation-ready CLI for bot/API integration

**Tech Stack:** `Python` `Streamlit` `APIs` `Automation`

**Impact:** Streamlines security research and threat intelligence workflows

---

### 🛡️ [Email Phishing Detector V3](https://github.com/Kajoldave173/email-phishing-detection)

**Multi-faceted phishing detection with OCR, threat intelligence, and AI assessment**

Analyzes email files (.eml, .msg) using header analysis, content inspection, VirusTotal threat intelligence, OCR for images, and AI-powered triage. Features persistent caching and async processing for production scalability.

**Key Features:**
- Comprehensive parsing with authentication result analysis (SPF, DKIM, DMARC)
- OCR integration extracting text from image attachments (Tesseract, Pillow)
- VirusTotal API v3 integration with SQLite caching via aiohttp
- AI-powered structured assessment with phishing scores and confidence
- Detailed colorized console reports with optional JSON export

**Tech Stack:** `Python` `aiohttp` `aiosqlite` `Tesseract` `OpenRouter API` `colorama`

**Impact:** Automates security analysis with explainable AI-driven threat assessment

---

### 🎲 [Stockastic: ML-Powered Stock Forecasting](https://github.com/Kajoldave173/stockastic)

**Interactive stock price prediction app with ARIMA time-series forecasting**

Built a web-based stock analysis platform fetching real-time financial data from Yahoo Finance and generating multi-day price forecasts using ARIMA models with interactive Plotly visualizations.

**Key Features:**
- Real-time data fetching with YFinance API integration
- ARIMA time-series forecasting with StatsModels
- Interactive financial charts with historical and forecast views
- Responsive Streamlit design working on all devices

**Tech Stack:** `Python` `Streamlit` `YFinance` `StatsModels` `Plotly`

**Disclaimer:** Educational tool for investment research, not financial advice

---

### 🔄 [DriftGuard: ML Lifecycle Automation](https://github.com/Kajoldave173/driftguard)

**End-to-end ML lifecycle with drift detection and auto-retraining**

Built a closed-loop system demonstrating train → track (MLflow) → serve (FastAPI) → detect drift → auto-retrain. Achieved **44.6% MAE reduction** on held-