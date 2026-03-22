<div align="center">

<!-- Dynamic Header Banner -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Vijaya%20Raghavendra&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=Data%20Analyst%20%7C%20Healthcare%20Analytics%20%7C%20ML%20Engineer&descColor=90cdf4&descAlignY=58&animation=fadeIn"/>

<!-- Typing SVG -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=38BDF8&center=true&vCenter=true&width=700&lines=Turning+Raw+Data+into+Real+Decisions;Healthcare+%26+Enterprise+Analytics+Specialist;SQL+%7C+Python+%7C+Power+BI+%7C+Azure+%7C+Snowflake;Building+Predictive+Models+that+Matter)](https://git.io/typing-svg)

<br/>

<!-- Badges Row -->
![Profile Views](https://komarev.com/ghpvc/?username=vijayraghavendra&color=38bdf8&style=flat-square&label=Profile+Views)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com)
[![Email](https://img.shields.io/badge/Email-vijayraghavendra300%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:vijayraghavendra300@gmail.com)

</div>

---

## 👨‍💻 About Me

```python
analyst = {
    "name"        : "Vijaya Raghavendra Adusumilli",
    "role"        : "Data Analyst — Healthcare & Enterprise Analytics",
    "experience"  : "3+ years",
    "location"    : "Mount Pleasant, MI 🇺🇸",
    "education"   : "M.S. Information Systems (Business Data Analytics) — Central Michigan University",
    "focus_areas" : ["Healthcare Analytics", "ETL Engineering", "Predictive Modeling", "BI Dashboards"],
    "currently"   : "Building AI-assisted analytics pipelines @ CitiusTech",
    "fun_fact"    : "I once recovered $1.2M in claim leakage with a root-cause SQL query 🎯"
}
```

> Results-driven analyst who bridges the gap between **complex healthcare datasets** and **clear business decisions** — using SQL, Python, Power BI, and a good dose of ML where it counts.

---

## 🛠️ Tech Stack

<div align="center">

### 🔍 Languages & Querying
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/Advanced%20SQL-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

### 📊 BI & Visualization
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Looker](https://img.shields.io/badge/Looker-4285F4?style=for-the-badge&logo=looker&logoColor=white)
![Excel](https://img.shields.io/badge/Excel%20Advanced-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

### ☁️ Cloud & Data Platforms
![Azure](https://img.shields.io/badge/Microsoft%20Azure-0089D6?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=for-the-badge&logo=googlebigquery&logoColor=white)
![AWS](https://img.shields.io/badge/AWS%20Redshift-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)

### ⚙️ Data Engineering & ETL
![Azure Data Factory](https://img.shields.io/badge/Azure%20Data%20Factory-0089D6?style=for-the-badge&logo=microsoftazure&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)

### 🤖 Machine Learning & AI
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI%20API-412991?style=for-the-badge&logo=openai&logoColor=white)

</div>

---

## 🚀 Featured Project

<div align="center">

### 🏥 Predictive Readmission Risk — Clinical ML Pipeline

</div>

> **Can we predict which patients will be readmitted within 30 days — before they're even discharged?**

A production-grade machine learning pipeline designed to identify **high-risk patients** for 30-day hospital readmission, enabling clinical teams to intervene proactively and reduce preventable readmissions.

```
📦 Predictive Readmission Risk
 ┣ 📂 data_ingestion        → EHR & claims data pipelines (Azure Data Factory + Snowflake)
 ┣ 📂 feature_engineering   → Diagnosis codes, LOS, prior visits, comorbidity scoring
 ┣ 📂 modeling              → Logistic Regression, Random Forest, XGBoost ensemble
 ┣ 📂 evaluation            → ROC-AUC, Precision-Recall, SHAP explainability
 ┣ 📂 deployment            → Streamlit dashboard + Power BI integration
 ┗ 📂 compliance            → HIPAA-compliant anonymization & RBAC controls
```

**🔬 What it does:**
- Ingests structured EHR data (diagnoses, procedures, labs, vitals) and claims records from Snowflake
- Engineers 40+ clinical and operational features including **Charlson Comorbidity Index**, prior admission frequency, and discharge disposition
- Trains an **XGBoost + Logistic Regression ensemble** model achieving **AUC-ROC of 0.84** on held-out validation sets
- Uses **SHAP values** to surface the top risk drivers per patient — making predictions *explainable* for clinicians, not just accurate
- Outputs a **Power BI risk dashboard** flagging high-risk patients pre-discharge, with real-time score refresh on new admissions
- Fully HIPAA-compliant with data masking on PHI fields and role-based access controls across the pipeline

**🛠️ Stack:** `Python` · `Scikit-learn` · `XGBoost` · `SHAP` · `Snowflake` · `Azure Data Factory` · `dbt` · `Power BI` · `Streamlit`

---

## 📈 What I Bring to the Table

| Area | What I Do |
|---|---|
| 🔎 **Analytics** | EDA, A/B Testing, Hypothesis Testing, Root Cause Analysis on 5M+ row datasets |
| 🏗️ **Data Engineering** | ETL pipeline design with ADF, dbt, Airflow — reduced data latency from 24hrs → 2hrs |
| 📊 **BI & Reporting** | 15+ executive dashboards in Power BI & Tableau tracking KPIs across claims & operations |
| 🤖 **ML & Forecasting** | Time-series (ARIMA, Prophet), classification, regression — improved planning accuracy by ~22% |
| 🏥 **Healthcare Domain** | Claims adjudication, denial management, HIPAA compliance, fraud detection, reimbursement analysis |
| ⚡ **AI-Assisted Analytics** | LLM-powered SQL generation (Snowflake Cortex), NL-to-SQL assistants, GenAI report summarization |

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=vijayraghavendra&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=vijayraghavendra&layout=compact&langs_count=8&theme=tokyonight&hide_border=true"/>

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=vijayraghavendra&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

</div>

---

## 🌐 Domain Expertise

```
Healthcare Analytics          ████████████████████  Expert
SQL & Query Optimization      ████████████████████  Expert
Power BI / Tableau            ████████████████░░░░  Advanced
Python (Pandas, Sklearn)      ███████████████░░░░░  Advanced
Cloud Platforms (Azure, SF)   ██████████████░░░░░░  Advanced
ETL / Data Engineering        ████████████░░░░░░░░  Proficient
Machine Learning              ███████████░░░░░░░░░  Proficient
GenAI / LLM Integration       █████████░░░░░░░░░░░  Growing
```

---

## 💡 Philosophy

> *"Data without context is noise. Analytics without action is art. The goal is always the decision at the end."*

I believe the best data analysts aren't just technical — they're translators. I translate messy healthcare data into stories that executives can act on, operations teams can trust, and patients ultimately benefit from.

---

<div align="center">

**📬 Let's connect and build something meaningful with data.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vijayraghavendra300@gmail.com)

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer"/>

</div>
