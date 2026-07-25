## Hi there 👋
from pathlib import Path

readme = r'''<div align="center">

# Hi, I'm Syed Muhammad Usama 👋

### Product-minded builder bridging business processes, data, automation, and AI

I turn operational problems into structured workflows, usable systems, and data-informed decisions.

[![Profile Views](https://komarev.com/ghpvc/?username=Usamasyyed&style=flat-square)](https://github.com/Usamasyyed)
[![GitHub followers](https://img.shields.io/github/followers/Usamasyyed?style=flat-square)](https://github.com/Usamasyyed?tab=followers)

</div>

---

## 🚀 What I work on

- **AI-enabled product workflows** — translating messy real-world inputs into reliable, reviewable outputs
- **Business process improvement** — mapping As-Is processes, finding bottlenecks, and designing practical To-Be workflows
- **Data analytics** — using SQL, Python, and Power BI to turn raw data into decisions
- **CRM and automation** — connecting business needs with scalable digital systems

I enjoy working where **business, technology, operations, and product thinking** meet.

---

## 🔭 Selected work

<table>
<tr>
<td width="50%" valign="top">

### 📊 [Vendor Performance Analysis](https://github.com/Usamasyyed/Vendor_Data_Analysis)

End-to-end analysis of **15.6M+ records** covering vendor profitability, inventory turnover, purchasing, freight, and discount effectiveness.

**Highlights**
- SQL data modelling and multi-source joins
- Python-based EDA and statistical testing
- Pareto, margin, stock-turnover, and inventory insights
- Interactive Power BI dashboard

`SQL Server` `Python` `Power BI` `Statistics`

</td>
<td width="50%" valign="top">

### 🛍️ [Customer Behaviour Analysis](https://github.com/Usamasyyed/Customer_behaviour_analysis)

A complete analytics pipeline exploring revenue patterns, customer segments, subscriptions, discounts, and product performance.

**Highlights**
- Data cleaning and feature preparation
- Business-focused SQL analysis
- Customer and revenue segmentation
- Interactive Power BI reporting

`Python` `Pandas` `SQL Server` `Power BI`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🧾 [Target E-commerce SQL Project](https://github.com/Usamasyyed/Target-ecommerce-sql-project)

SQL-driven exploration of e-commerce orders, customers, sellers, payments, and operational patterns.

**Focus**
- Business-question-driven analysis
- Joins, aggregations, CTEs, and window functions
- Translating transactional data into actionable findings

`SQL` `E-commerce Analytics` `Business Intelligence`

</td>
<td width="50%" valign="top">

### 🧠 [SQL Data Analytics](https://github.com/Usamasyyed/SQL_data_analytics)

A growing collection of hands-on SQL analysis work focused on querying, modelling, and extracting practical business insights.

**Focus**
- Data exploration
- Analytical SQL
- Structured problem solving
- Decision-oriented reporting

`SQL` `Data Analysis` `Problem Solving`

</td>
</tr>
</table>

---

## 🔒 Private product work

Some of my most substantial work is in private repositories because it was developed for real business use.

### Engineering Drawing BOM Extraction

An AI-assisted workflow that turns complex engineering drawings into structured BOM data.

- Table-region detection and document segmentation
- Metadata and nested BOM extraction
- Structured JSON contracts
- Validation and human-review workflows
- Designed for real manufacturing documentation

### Automated Logo & Marking Replacement

A computer-vision and OCR-supported tool for detecting and replacing customer logos and text markings across engineering drawing PDFs.

- Object detection across varied drawing layouts
- OCR-based, location-independent text removal
- PDF/image processing and output validation
- Confidence thresholds, fallbacks, and review tooling
- Iteratively improved using real customer drawings

> These repositories remain private to protect client data, implementation details, and proprietary workflows.

---

## 🧩 Currently exploring

### AI-assisted estimating for remodelers

Designing an end-to-end workflow that converts unstructured project descriptions, measurements, selections, and attachments into a reviewable estimate package.

The work explores:

- scope detection and missing-scope analysis
- targeted clarification workflows
- measurement and selection readiness
- structured estimate generation
- deterministic logic, AI reasoning, and human review
- evaluation datasets for testing reliability

---

## 🛠️ Toolbox

### Product & Delivery
`Product Discovery` `Requirements Engineering` `User Stories` `Acceptance Criteria` `UAT` `Agile` `Process Mapping`

### Data & AI
`Python` `SQL` `Power BI` `Pandas` `Computer Vision` `OCR` `LLM Workflows` `JSON`

### Business Systems
`Zoho` `Salesforce` `Microsoft Dynamics 365` `Power Platform` `CRM/ERP Workflows`

### Collaboration
`Jira` `Confluence` `GitHub` `Stakeholder Workshops` `Cross-functional Delivery`

---

## 📈 GitHub activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Usamasyyed&show_icons=true&hide_border=true&rank_icon=github" alt="Usama's GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Usamasyyed&layout=compact&hide_border=true" alt="Top languages" />

</div>

---

## 🌱 A little more about me

- 🎓 Industrial Engineering background with a Master's focus on Business & Technology
- 🧭 Career path: Process Analyst → Product Owner → CRM Consultant → AI Product Lead
- 🏗️ I like building systems that make complicated work easier
- ♟️ Outside work: chess, badminton, cooking, and exploring new product ideas
- 📍 Based in Tampere, Finland

---

<div align="center">

### Let's build useful things.

Explore my repositories, follow the projects, or connect with me through GitHub.

</div>
'''

path = Path("/mnt/data/README.md")
path.write_text(readme, encoding="utf-8")
print(f"Created {path} ({path.stat().st_size} bytes)")

<!--
**Usamasyyed/Usamasyyed** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
