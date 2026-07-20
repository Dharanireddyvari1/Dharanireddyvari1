<h1 align="center">Hi, I'm Dharani 👋</h1>
<h3 align="center">Staff Technologist · Data Pipelines, Web Scraping & Entity Resolution</h3>

<p align="center">
  <a href="mailto:reddyvaridharani05@gmail.com">📧 Email</a> ·
  <a href="https://www.linkedin.com/in/dharani-r-56218a419/">💼 LinkedIn</a> ·
  <a href="https://dharanireddyvari.vercel.app/">🌐 Portfolio</a> ·
</p>

---

### About me

I build and maintain data pipelines, scrapers, and research tools that turn messy, real-world
public data into structured, credible outputs people actually rely on — journalists,
policymakers, researchers, and downstream ML systems. 4+ years across patent intelligence,
pharma/regulatory data, and large-scale client scraping infrastructure.

What I care about most: **data credibility**. Every pipeline I build makes its assumptions,
exclusions, and confidence levels visible — not just to me, but to non-technical people who have
to trust the output.

- 🔭 Currently building end-to-end scraper + entity-resolution infrastructure for public patent
  intelligence at **Patent Gap AI**
- 🧩 Recently built a full entity-resolution pipeline matching messy correctional-facility records
  to jurisdictions for a public telecom-rate database (see pinned repo below)
- 🌱 Interested in where deterministic data pipelines and LLM-assisted review genuinely
  complement each other — and where they shouldn't be mixed
- 💬 Ask me about: web scraping at scale, entity resolution / record linkage, PDF & OCR
  extraction, making pipelines legible to non-technical stakeholders

---

### Tech stack

**Python & Data**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**Web Scraping**
![Scrapy](https://img.shields.io/badge/Scrapy-60A839?style=flat&logo=scrapy&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat&logo=selenium&logoColor=white)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-white?style=flat)

**APIs, LLMs & Extraction**
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat&logo=openai&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)

**PDF & Documents**
![PyMuPDF](https://img.shields.io/badge/PyMuPDF-red?style=flat)
![Tesseract OCR](https://img.shields.io/badge/Tesseract_OCR-4285F4?style=flat)

**Automation & Infra**
![Airflow](https://img.shields.io/badge/Apache_Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)

**Databases**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat&logo=snowflake&logoColor=white)

---

### Featured projects

**🔗 [Telecom Rate Entity-Resolution Pipeline](#)**
Matches messy correctional-facility phone-rate records to county/state jurisdictions —
classification + fuzzy record linkage (`recordlinkage`) with deterministic tie-breaking, an
optional LLM-assisted review layer for low-confidence matches (isolated and clearly flagged, off
by default), full test coverage, and an interactive Streamlit dashboard. Built to be reusable
across future data providers via a config-driven ruleset rather than hardcoded logic.
`Python` `pandas` `recordlinkage` `Streamlit` `pytest`

**🔗 [Airflow-Orchestrated Data Validation Framework](#)**
Apache Airflow pipeline automating recurring rule-based validation, anomaly detection, and
failure logging across batch ingestion workflows, with reusable validation modules documented for
non-technical maintainers.
`Python` `Apache Airflow` `Data Validation`

**🔗 [Airbnb Distributed Batch ETL — PySpark on AWS EMR Serverless](#)**
Cloud-native ETL pipeline collecting, transforming, and structuring raw public web data into
validated analytical outputs, with schema validation, deduplication, and Glue Catalog metadata
registration.
`PySpark` `AWS EMR Serverless` `Spark SQL` `Glue`

**🔗 [Best Buy PDP Scraper](#)**
Production-grade scraper for a complex, bot-protected source — structured error handling, retry
logic, proxy rotation, and logging.
`Python` `Scraping` `Proxy Rotation`

> Replace the `#` links above with your actual repo URLs once each project is pushed.

---

### Experience snapshot

- **AI Engineer, Data Infrastructure & Research Tools** — Patent Gap AI *(Mar 2026–Present)*
  End-to-end scraper + entity-resolution pipeline across USPTO, Google Patents, and Free Patents
  Online; PDF/OCR extraction; LLM-assisted structured extraction; Airflow + GitHub Actions
  automation.
- **AI / ML Engineer** — AbbVie *(Aug 2025–Jan 2026)*
  PySpark pipelines for clinical document data; LLM-based extraction from regulatory documents;
  containerized deployment on AWS.
- **Software Engineer, Data Engineering** — Dentsu Global Services *(Dec 2022–Jul 2024)*
  Owned scraper infrastructure across 13+ global sources; 300K+ records/week; Jenkins + GitHub
  Actions automation at ≥95% reliability.

---

### Education
**M.S. Applied Statistics — Data Science Specialization**, Colorado State University (2024–2025)
**B.E. Mechanical Engineering**, Coimbatore Institute of Technology (2018–2022)

---

<p align="center"><i>Open to Staff Technologist / Data Engineering roles focused on public-interest data and research tooling.</i></p>
