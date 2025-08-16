# Hi 👋, I'm Diego Porto

**Data Analyst | Power BI & Python Enthusiast | Turning Data into Insights**  
From João Pessoa, Brazil

[![Power BI](https://img.shields.io/badge/Power%20BI-30363D?logo=powerbi&logoColor=F2C811)](#)
[![SQL](https://img.shields.io/badge/SQL-30363D?logo=postgresql&logoColor=white)](#)
[![Python](https://img.shields.io/badge/Python-30363D?logo=python)](#)
[![Email](https://img.shields.io/badge/Email-diego.porto10%40gmail.com-30363D)](mailto:diego.porto10@gmail.com)
![Location](https://img.shields.io/badge/Jo%C3%A3o%20Pessoa%2C%20BR-UTC%E2%88%9203-30363D)

---

## About Me

I’m a data analyst passionate about transforming raw information into clear, actionable insights.  
I focus on **clean data models**, **clear KPIs**, and **pragmatic storytelling**.

- 🐍 **Python for Data Science** (Pandas, NumPy, Matplotlib, Seaborn)  
- 📊 **Data Visualization** with **Power BI**  
- 🗄️ **SQL** for querying and modeling  
- 🧭 Building dashboards that support decision-making

---

## Featured Projects

### 1) HR Analytics — **Attrition & Tenure** (Power BI)
**Domain:** People Analytics • **Stack:** Power BI, Power Query, SQL • **Dataset:** IBM HR (public)

Explored attrition drivers (**overtime**, **travel frequency**, **compa-ratio**).  
Segmented risk cohorts and proposed retention levers prioritized by **impact vs. cost**.

**Live demos**  
<img src="https://raw.githubusercontent.com/diegoporto10/hr-analytics-attrition/main/assets/overview_demo.gif" alt="HR Overview demo" width="560"><br>
<img src="https://raw.githubusercontent.com/diegoporto10/hr-analytics-attrition/main/assets/quickwins_demo.gif" alt="HR Quick Wins demo" width="560">

**Links:**  
- ▶ **View Dashboard (PBIX)**: [Download](https://github.com/diegoporto10/hr-analytics-attrition/raw/main/HR-Attrition-Overview.pbix)  
- 💻 **GitHub Repo**: https://github.com/diegoporto10/hr-analytics-attrition  
- 📝 **Case Study**: in repo README (Assets & notes included)

---

### 2) Retail Sales Intelligence — **Executive BI**
**Domain:** Retail • **Stack:** Power BI, DAX, Excel • **Dataset:** Kaggle (5k+ rows)

Identified a **12% MoM drop** tied to stockouts; recommended **inventory buffer** and **vendor consolidation**.

![Retail Executive Overview](https://raw.githubusercontent.com/diegoporto10/retail-sales-intelligence-pbi/refs/heads/main/images/executive-overview.png)

**Links:**  
- ▶ **View Dashboard (PBIX)**: [Download](https://github.com/diegoporto10/retail-sales-intelligence-pbi/raw/main/Retail%20Sales%20Intelligence.pbix)  
- 💻 **GitHub Repo**: https://github.com/diegoporto10/retail-sales-intelligence-pbi  
- 📝 **Case Study**: https://github.com/diegoporto10/retail-sales-intelligence-pbi/blob/main/docs/case-study.md

---

### 3) Python **Data Cleaning Script**
**Goal:** Reusable Pandas pipeline for fast data cleaning (rename/trim, type fixing, dedupe, coercions, and deriving age/tenure bands).

**Repo:** https://github.com/diegoporto10/data-cleaning-python

**Quickstart (Windows / PowerShell):**
```powershell
python -m venv .venv && .\.venv\Scripts\activate
pip install -r requirements.txt

# Run
python src\clean.py --input data\raw\sample.csv ^
                    --output data\processed\clean.csv ^
                    --int-cols age,years_at_company
