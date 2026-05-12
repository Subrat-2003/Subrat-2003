<div align="center">

# Hi, I'm Subrat 👋

**Data Analyst · AI/ML Engineer · Data Scientist**

*I build data systems that are honest about their limits and useful in production.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/subrat-kumar-jena)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Subrat-2003)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/spaces/Sk-Jena/sec-risk-dashboard)

</div>

---

## 🧠 What I Build

I work at the intersection of **data engineering**, **machine learning**, and **business intelligence** — turning messy, large-scale datasets into systems that stakeholders can actually trust.

- 🏗️ **Data pipelines** that handle the dirty work — malformed HTML, schema drift, 60GB+ of raw filings
- 📊 **Dashboards and KPI systems** built for non-technical consumers, not just engineers
- 🤖 **ML pipelines** where integrity matters more than headline accuracy
- 🔄 **Automated retraining workflows** that stay accurate without manual intervention

---

## 🚀 Featured Projects

### 🏦 [Financial Distress Early Warning System (FDEWS)](https://github.com/Subrat-2003/Financial-distress-early-warning-system)
> **Architected a Polars-based out-of-core pipeline for 60GB+ SEC EDGAR filings on commodity hardware → Corporate insolvency prediction 12 months ahead**

Medallion architecture (Bronze → Silver → Gold) | Polars Lazy Evaluation | FinBERT MD&A sentiment | XGBoost production model

- **4.5× lift** over the **8.4% baseline** crash rate
- **XGBoost**: 87% recall, 38% precision, **F1 0.52** | **1,786 false positives** vs LSTM's 24,652
- **Feature Order Lock** prevents silent prediction drift at inference time
- 🔴 [**Live Demo** — HuggingFace Spaces](https://huggingface.co/spaces/Sk-Jena/sec-risk-dashboard)

`Polars` `Parquet` `FinBERT` `XGBoost` `SHAP` `DuckDB` `Streamlit` `BeautifulSoup`

---

### 💸 [Cashflow Forecasting & Risk Simulation](https://github.com/Subrat-2003/Cashflow-Forecasting-and-Risk-Simulation-for-Freelancers)
> **Stochastic financial runway modeling for gig economy income volatility**

Full-stack forecasting platform | Hybrid stacking ensemble | Nightly automated retraining

- **XGBoost (0.6) + Random Forest (0.4)** ensemble generating bounded planning ranges from **rolling forecast-error variance**
- **SHA-256** fingerprinting for immutable data lineage across retraining cycles
- **Sub-200ms** query response via Supabase SECURITY DEFINER views
- 🔴 [**Live Demo** — Vercel](https://cashflow-forecasting-and-risk-simul.vercel.app)

`FastAPI` `XGBoost` `Next.js 14` `TypeScript` `Supabase` `PostgreSQL` `GitHub Actions`

---

### 🏷️ [Loan Approval Prediction](https://github.com/Subrat-2003/Loan-Approval-Prediction-ML)
> **I reduced model accuracy from 98% to 88% — and that was the win.**

Found a data leakage flaw (pre-split oversampling → synthetic duplicates bleeding into test set). Rebuilt from scratch.

- **11 classifiers × 100 randomised partitions** → macro F1 **0.81**, rejected-class F1 **0.71** on leakage-proof holdout
- **CatBoost** selected for consistency, not peak score
- Feature importance: **Credit History ~24%**, Loan Amount ~19%, Applicant Income ~18%

`Scikit-Learn` `CatBoost` `XGBoost` `imbalanced-learn` `Pandas` `Seaborn`

---

### 🔍 [Veri-Vigil AI](https://github.com/Subrat-2003) — ET GenAI Hackathon 2026
> **Browser-based content trust analyzer | ET GenAI Hackathon Semi-Finalist**

Chrome Extension (Manifest V3) that analyses YouTube video metadata and generates a trust score + explanation using LLaMA 3.1 via Groq API.

`FastAPI` `LLaMA 3.1` `Groq` `Chrome Extension` `Manifest V3`

---

## 🛠️ Tech Stack

**Languages & Querying**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)

**ML & Data Engineering**

![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square&logo=xgboost&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Polars](https://img.shields.io/badge/Polars-CD792C?style=flat-square&logo=polars&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**Visualization & BI**

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)

**Infrastructure & DevOps**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

![](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Subrat-2003&theme=github_dark)

![Top Languages](https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Subrat-2003&theme=github_dark)

![GitHub Streak](https://streak-stats.demolab.com?user=Subrat-2003&theme=github-dark&hide_border=true)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Subrat-2003/Subrat-2003/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Subrat-2003/Subrat-2003/output/github-contribution-grid-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/Subrat-2003/Subrat-2003/output/github-contribution-grid-snake.svg" />
</picture>

</div>

---

## 🏆 Highlights

- 🎯 **OJEE 2023** — Top 5% Merit rank (800 / 16,000+ candidates)
- 🥈 **ET GenAI Hackathon 2026** — Semi-Finalist | Built Veri-Vigil AI in 48 hours
- 🏅 **Trithon 2023** — Cash Prize winner for problem-solving and technical collaboration
- 📄 **RAECC-2025 National Conference** — Presented research on E-Waste upcycling into Biodegradable 3D Printing Filaments
- 🎓 **B.Tech CSE (AI)** — GIFT Autonomous, Bhubaneswar | Graduating in June 2026

---

## 📬 Let's Connect

I'm actively looking for **Data Analyst, AI/ML Engineer, and Business Intelligence** roles — available full-time from **June 2026**, open to relocation.

[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:subratjena2911@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/subrat-kumar-jena)

---

<div align="center">

*"The model that admits its flaws is the one you can trust in production."*

</div>
