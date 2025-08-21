# Hi 👋, I'm Diego Porto

**Data Analyst | Power BI & Python Enthusiast | Turning Data into Insights**  
From João Pessoa, Brazil (UTC−03)

[![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Viz-FFB900?logo=powerbi&logoColor=white)](#)
[![SQL](https://img.shields.io/badge/SQL-Data%20Modeling-2F74C0?logo=microsoftsqlserver&logoColor=white)](#)
[![Python](https://img.shields.io/badge/Python-Data%20Wrangling-3776AB?logo=python&logoColor=white)](#)
[![Email](https://img.shields.io/badge/Email-diego.porto10%40gmail.com-595959?logo=gmail&logoColor=white)](mailto:diego.porto10@gmail.com)

---

## About Me

I’m a data analyst passionate about transforming raw information into clear, actionable insights.  
I focus on **clean data models**, **clear KPIs**, and **pragmatic storytelling**.

- 🐍 **Python for Data Science** (Pandas, NumPy, Matplotlib, Seaborn)  
- 📊 **Visualization** (Power BI, Tableau)  
- 🧱 **SQL** for querying & modeling  
- 🧭 **Dashboards** that support decision-making

---

## Featured Projects

### 1) HR Analytics — Attrition & Tenure (Power BI)

**Domain:** People Analytics • **Stack:** Power BI, Power Query, SQL • **Dataset:** IBM HR (public)

Explored attrition drivers (overtime, travel frequency, compa-ratio).  
Segmented risk cohorts and proposed retention levers prioritized by impact vs. cost.

**Live demos**

<img src="https://raw.githubusercontent.com/diegoporto10/hr-analytics-attrition/main/assets/overview_demo.gif" width="820" alt="HR Analytics — Overview demo">

<img src="https://raw.githubusercontent.com/diegoporto10/hr-analytics-attrition/main/assets/quickwins_demo.gif" width="820" alt="HR Analytics — Quick Wins demo">

**Links:**

- 📊 **View Dashboard (PBIX):**  
  [Download](https://github.com/diegoporto10/hr-analytics-attrition/raw/main/HR-Attrition-Overview.pbix)
- 📁 **GitHub Repo:**  
  https://github.com/diegoporto10/hr-analytics-attrition
- 📝 **Case Study:**  
  See **assets & notes** in the repo README

---

### 2) Retail Sales Intelligence — Executive BI

**Domain:** Retail • **Stack:** Power BI, DAX, Excel • **Dataset:** Kaggle (5k+ rows)

Identified a **12% MoM drop** tied to stockouts; recommended **inventory buffer** & **vendor consolidation**.

<img src="https://raw.githubusercontent.com/diegoporto10/retail-sales-intelligence-pbi/refs/heads/main/images/executive-overview.png" width="820" alt="Retail Executive Overview">

**Links:**

- 📊 **View Dashboard (PBIX):**  
  [Download](https://github.com/diegoporto10/retail-sales-intelligence-pbi/raw/main/Retail%20Sales%20Intelligence.pbix)
- 📁 **GitHub Repo:**  
  https://github.com/diegoporto10/retail-sales-intelligence-pbi
- 📝 **Case Study:**  
  https://github.com/diegoporto10/retail-sales-intelligence-pbi/blob/main/docs/case-study.md

---

### 3) João Pessoa Real Estate — Market Insights

**Domain:** Real Estate • **Stack:** Power BI, Python (Pandas, Matplotlib), SQL • **Dataset:** Local listings & indexes  

Analyzed **João Pessoa’s housing market**, with focus on:  
- 📈 **Property appreciation trends**  
- ⚖️ **Risk vs. return analysis**  
- 🏙 **Quality of life index by neighborhood**  

<img src="https://raw.githubusercontent.com/diegoporto10/joao-pessoa-real-estate/main/images/qualidade-de-vida.png" width="820" alt="Quality of Life by Neighborhood">

<img src="https://raw.githubusercontent.com/diegoporto10/joao-pessoa-real-estate/main/images/risco-vs-retorno.png" width="820" alt="Risk vs Return">

<img src="https://raw.githubusercontent.com/diegoporto10/joao-pessoa-real-estate/main/images/valorizacao.png" width="820" alt="Property Value Appreciation">

**Links:**

- 📊 **View Dashboard (PBIX):**  
  [Download](https://github.com/diegoporto10/joao-pessoa-real-estate/raw/main/Análises%20Imobiliárias.pbix)
- 📁 **GitHub Repo:**  
  https://github.com/diegoporto10/joao-pessoa-real-estate
- 📄 **Report (PDF):**  
  [Quality of Life Index](https://github.com/diegoporto10/joao-pessoa-real-estate/raw/main/Quality%20of%20life%20index%20by%20Neighborhood.pdf)

---

### 4) Python Data Cleaning Script

**Goal:** Reusable Pandas pipeline for fast data cleaning (rename/trim, type fixing, dedupe, coercions, and deriving age/tenure bands).

**Repo:** https://github.com/diegoporto10/data-cleaning-python

**Quickstart (Windows / PowerShell):**
```powershell
# 1) Create & activate venv
python -m venv .venv &&
.\.venv\Scripts\activate

# 2) Install dependencies
pip install -r requirements.txt

# 3) Run cleaner
python src\clean.py --input data\raw\sample.csv ^
                    --output data\processed\clean.csv ^
                    --int-cols age,years_at_company
