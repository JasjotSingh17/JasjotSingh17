# Jasjot Singh

**Data Analyst** · Waterloo, ON · [LinkedIn](https://www.linkedin.com/in/jasjot-singh-4583ab203/) · [Email](mailto:j367sing@uwaterloo.ca)

---

I'm a math graduate from the University of Waterloo who builds things with data — pipelines, statistical models, and dashboards that turn messy datasets into decisions people can act on.

I care about getting the *why* right, not just running the numbers. That means choosing the right statistical test for the right reason, designing data models that actually support the questions being asked, and making findings legible to someone who isn't staring at the same spreadsheet I am.

Currently looking for my first full-time Data Analyst role. Open to Waterloo, Toronto, or remote.

---

## Projects

### 🤖 F1 Natural Language Query Agent

`Python` `LangGraph` `Ollama` `SQLite` `Agentic AI`

Ask a question about an F1 season in plain English, get a correct answer back — no SQL required. Built a LangGraph agent that generates SQL from natural language, validates it against a strict read-only ruleset before execution, and self-corrects through a retry loop if a query fails. Runs entirely on a local open-source model via Ollama. The interesting part isn't the happy path — it's watching the agent observe its own error and fix the query on the second attempt.

→ [View project](https://github.com/JasjotSingh17/f1-nl-to-sql-agent)

---

### 🚔 SF Police Stop Patterns

`Python` `SciPy` `Statsmodels` `Power BI` `Star Schema`

Analysed 905,070 police stop records to investigate racial disparities and time-based arrest patterns. Built a star schema data model powering interactive Power BI dashboards, then ran four hypothesis tests — each chosen for a specific statistical reason — to separate real patterns from noise. Night stops carry a 33% higher arrest rate than day stops. That difference is not sampling noise (z-test, p < 0.001).

→ [View project](https://github.com/JasjotSingh17/SF_policing_analysis)

---

### 🏎️ F1 Driver Consistency Analysis

`Python` `FastF1 API` `SQLite` `SQLAlchemy` `Power BI`

Championship points tell you who won. They don't tell you who was *reliable*. Built a Consistency Score across four dimensions — lap stability, position variance, teammate comparison, and DNF rate — then combined it with points-per-race into a single index that identifies drivers who balance peak performance with race-to-race dependability. Teammate normalisation controls for car performance, isolating the driver's actual contribution.

→ [View project](https://github.com/JasjotSingh17/F1-Project)

---

### 📡 GitHub DA Tool Trend Tracker

`Python` `GitHub API` `SQLite` `SQL Window Functions` `Power BI`

I kept seeing conflicting advice about which DA tools are actually worth learning. So I pulled the data. Built an ETL pipeline across 30+ tools in 7 skill categories, used SQL window functions to generate week-over-week adoption rankings, and delivered the findings in a 4-page Power BI dashboard. Python is a statistical outlier by every measure. SQL is the non-negotiable foundation. DuckDB is worth watching.

→ [View project](https://github.com/JasjotSingh17/Github-project)

---

### 🏬 Superstore Sales EDA

`Python` `Pandas` `Matplotlib` `Seaborn` `SciPy`

The Central Region wasn't underperforming because of weak demand — it was a margin problem. Discounts above 20% are loss-making on average (confirmed via regression, p < 0.001). Tables and Bookcases generate revenue and destroy profit simultaneously.

→ [View project](https://github.com/JasjotSingh17/Superstore-EDA)

---

## Skills

| | |
|---|---|
| **Languages** | Python, SQL, R |
| **Analytics** | Pandas, Statsmodels, SciPy, Matplotlib, Seaborn |
| **Visualisation** | Power BI (DAX, Power Query) |
| **Data Modelling** | Star Schema, Hypothesis Testing, Regression, Feature Engineering |
| **AI / Agentic Systems** | LangGraph, Ollama, Agentic Workflows, Tool-Calling |
| **Tools** | SQLite, SQLAlchemy, DuckDB, Git, Flask, Excel |

---

## Background

**University of Waterloo** — BMath (Honours), Mathematical Studies · Minor in Computer Science · Graduated Dec 2025

**Silverpush** — Data Analytics Intern, Summer 2023 · Python pipelines, SQL databases, Flask REST API

<!--

**JasjotSingh17/JasjotSingh17** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...

- 🌱 I’m currently learning ...

- 👯 I’m looking to collaborate on ...

- 🤔 I’m looking for help with ...

- 💬 Ask me about ...

- 📫 How to reach me: ...

- 😄 Pronouns: ...

- ⚡ Fun fact: ...

-->
