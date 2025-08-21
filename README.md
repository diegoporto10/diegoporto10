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
- 📊 **Visualization** (Power BI)  
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

### 3) Python Data Cleaning Script

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

---

## 🏡 Real Estate Market in João Pessoa — Visual Insights  
## Mercado Imobiliário em João Pessoa — Análises Visuais

A visual analysis of João Pessoa’s neighborhoods from an investor’s perspective.  
Combines **quality of life**, **rental return vs. price**, and **historical & projected appreciation**.

Uma análise visual dos bairros de João Pessoa com foco em investimento imobiliário.  
Inclui dados sobre **qualidade de vida**, **retorno de aluguel x preço**, e **valorização histórica e projetada**.

---

### 📍 Quality of Life Index by Neighborhood  
### 📍 Índice de Qualidade de Vida por Bairro

<img src="images/qualidade-de-vida.png" width="820" alt="Quality of Life Map">

> **Insight**  
> Explore neighborhood-level differences in quality of life across João Pessoa to inform better real estate investment decisions.  
> Explore as diferenças de qualidade de vida entre os bairros de João Pessoa para decisões mais inteligentes de investimento imobiliário.

---

### 📈 Historical & Projected Real Estate Appreciation  
### 📈 Valorização Histórica e Projeção Futura de Imóveis

<img src="images/valorizacao.png" width="820" alt="Appreciation Forecast">

> **Insight**  
> Forecast based on historical appreciation data from 2020–2024. Includes confidence interval projections until 2029.  
> Projeção baseada nos dados históricos de valorização de imóveis entre 2020 e 2024. Inclui faixa de confiança com estimativas até 2029.

---

### ⚖️ Risk vs. Return — Rental Strategy Insights  
### ⚖️ Risco vs. Retorno — Estratégias de Aluguel

<img src="images/risco-vs-retorno.png" width="820" alt="Risk vs Return">

> **Insight**  
> Compare average property prices with long-term rental yields to assess profitability vs. risk across neighborhoods.  
> Compare os preços médios dos imóveis com os retornos esperados de aluguel de longo prazo para identificar os bairros mais lucrativos e com menor risco para investimento imobiliário.

---

## 🧠 Tools Used | Ferramentas Utilizadas

- Power BI (data modeling, visualization)  
- DAX for custom measures and forecasting  
- Public data on João Pessoa & Cabedelo real estate
