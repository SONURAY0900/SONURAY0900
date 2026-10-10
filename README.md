<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="./light.svg">
    <img src="./dark.svg" alt="Sonu Ray — Full-Stack Java Developer" width="1180">
  </picture>
</p>

<h1 align="center">Sonu Ray</h1>

<p align="center">
  <strong>Full-Stack Java Developer · Real-Time Systems · AI & Backend</strong>
</p>

<p align="center">
  Software Engineering Intern at <b>DRDO</b> · B.Tech CSE '27 · Building real-time systems and LLM-powered applications
</p>

<p align="center">
  <a href="https://github.com/YOUR_GITHUB_USERNAME"><img src="https://img.shields.io/badge/GitHub-0F172A?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
  <a href="https://www.linkedin.com/in/YOUR_LINKEDIN_USERNAME/"><img src="https://img.shields.io/badge/LinkedIn-2563EB?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:raysonu0900@gmail.com"><img src="https://img.shields.io/badge/Email-0891B2?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://sonuray.dev"><img src="https://img.shields.io/badge/Portfolio-7C3AED?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Open%20to-Internships%20%26%20Full--Time%202027-16A34A?style=flat-square" alt="Open to opportunities">
  <img src="https://img.shields.io/badge/Location-Bhubaneswar%2C%20India-64748B?style=flat-square" alt="Location">
  <img src="https://img.shields.io/badge/CGPA-8.39-F59E0B?style=flat-square" alt="CGPA">
</p>

---

## 👨‍💻 About

I build backend-heavy, real-time systems and practical AI applications. Recently I architected a LAN-based telemetry ground station at **DRDO PXE** and shipped a multi-agent **NL-to-SQL** system with guardrails at **Astro Vedangam**.

- 🎯 **Focus:** Scalable backends, real-time data pipelines, LLM-powered products
- ☕ **Primary stack:** Java · Spring Boot · Servlets/JSP · SQL · REST APIs
- ⚡ **Also working with:** React · Python · FastAPI · Groq / LLaMA · Prompt Engineering
- 🧩 **Interested in:** Distributed systems, networking (TCP/UDP), backend architecture, multi-agent AI
- 🎓 **Education:** B.Tech CSE, Trident Academy of Technology (BPUT) · 2023 – 2027 · CGPA 8.39
- 📍 **Based in:** Bhubaneswar, India

---

## 💼 Experience

| Role | Organization | Period | Stack |
|------|--------------|--------|-------|
| **Software Engineering Intern** | Defence Research & Development Organisation (DRDO), PXE Chandipur | Jun – Jul 2026 | Java · TCP/UDP · Real-Time Systems |
| **Software Development Intern** | Astro Vedangam Pvt. Ltd. | Sep 2025 – Jan 2026 | Python · FastAPI · LLMs |

<details>
<summary><b>DRDO PXE — UAS-RTMVD (Upper Air Sounding Real-Time Monitoring & Visualization Dashboard)</b></summary>
<br>

- Architected a **LAN-based Ground Station Terminal**, replacing a legacy standalone app and enabling centralized real-time monitoring of multiple distributed weather stations.
- Engineered a **low-latency TCP/UDP telemetry pipeline** with a custom **binary frame decoder** for continuous extraction of meteorological parameters with no manual data handling.
- Designed a real-time GUI with live sensor/GPS tables, multi-mode graphing (line, area, bar, scatter) and ascent summaries.
- Built the **DRDO Unified Station Launcher**, integrating three independent applications (AWS, Visibility Sensor, UASS) into one interface.
- Validated reliability via end-to-end testing with real and simulated telemetry; researched radar/laser/GNSS balloon-tracking for future integration.

</details>

<details>
<summary><b>Astro Vedangam — SmartQuery (Natural Language to SQL Agent)</b></summary>
<br>

- Architected a **4-stage multi-agent pipeline** (Intent → Generator → Guard → Explainer) with automated SQL validation that blocks destructive or hallucinated queries.
- Cut LLM prompt size by dynamically filtering `INFORMATION_SCHEMA` to relevant tables/columns, improving accuracy within token limits.
- Implemented an **auto-repair loop** that detects and fixes invalid SQL before execution.
- Deployed a FastAPI REST API with **Groq LLaMA 3.1** and cloud SQL Server on Render, with persistent query history.
- Researched Transformer architecture and local inference (Mistral 7B); documented the full architecture and setup for team handoff.

</details>

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🧠 [SmartQuery](https://github.com/YOUR_GITHUB_USERNAME/SmartQuery)
**Natural Language → SQL multi-agent system**

4-stage pipeline with a SQL Guard layer, schema-aware validation and auto-repair, targeting T-SQL on AdventureWorks 2016.

`Python` `FastAPI` `Groq` `LLaMA 3.1` `SQL Server` `Jinja2`

</td>
<td width="50%" valign="top">

### 📡 UAS-RTMVD
**Real-time weather telemetry ground station (DRDO PXE)**

LAN-based monitoring with a TCP/UDP pipeline, custom binary decoder and live multi-mode visualization.

`Java` `TCP/UDP` `Real-Time Systems` `GUI`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎬 [YouTube Video Recommendation Platform](https://github.com/YOUR_GITHUB_USERNAME/YOUR_YOUTUBE_REPO)
**Full-stack recommender with analytics**

YouTube Data API v3 + Oracle DB, Google OAuth 2.0 with role-based admin access, search-history reuse to cut API calls, Google Charts dashboard.

`Java` `JSP` `Servlet` `Oracle` `OAuth 2.0` `JDBC`

</td>
<td width="50%" valign="top">

### 💸 [PocketMoney](https://github.com/YOUR_GITHUB_USERNAME/YOUR_POCKETMONEY_REPO)
**Full-stack expense management system**

Session-based auth, normalized Oracle schema, sortable/filterable reports with monthly aggregation, Chart.js analytics, glassmorphism UI.

`Java` `JSP` `Servlet` `Oracle` `Chart.js`

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

**Languages**<br>
<img src="https://skillicons.dev/icons?i=java,c,python,js,html,css" alt="Languages">

**Backend & APIs**<br>
<img src="https://skillicons.dev/icons?i=spring,fastapi,nodejs" alt="Backend"> 
<img src="https://img.shields.io/badge/Servlets%20%2F%20JSP-0891B2?style=for-the-badge" alt="Servlets JSP">
<img src="https://img.shields.io/badge/REST%20APIs-0F172A?style=for-the-badge" alt="REST">

**Frontend**<br>
<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,bootstrap" alt="Frontend">

**Databases**<br>
<img src="https://skillicons.dev/icons?i=oracle,mysql,postgres" alt="Databases">
<img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" alt="SQL Server">
<img src="https://img.shields.io/badge/JDBC-2563EB?style=for-the-badge" alt="JDBC">

**Networking & Systems**<br>
<img src="https://img.shields.io/badge/TCP%2FUDP-0F172A?style=for-the-badge" alt="TCP UDP">
<img src="https://img.shields.io/badge/Binary%20Frame%20Decoding-475569?style=for-the-badge" alt="Binary frame decoding">

**AI / ML**<br>
<img src="https://img.shields.io/badge/LLM%20Integration-7C3AED?style=for-the-badge" alt="LLM Integration">
<img src="https://img.shields.io/badge/Prompt%20Engineering-6D28D9?style=for-the-badge" alt="Prompt Engineering">
<img src="https://img.shields.io/badge/Groq-111827?style=for-the-badge" alt="Groq">
<img src="https://img.shields.io/badge/Hugging%20Face-F59E0B?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face">
<img src="https://img.shields.io/badge/Multi--Agent%20Systems-DB2777?style=for-the-badge" alt="Multi-Agent Systems">

**Tools & Deployment**<br>
<img src="https://skillicons.dev/icons?i=git,github,vscode,eclipse,docker,netlify" alt="Tools">
<img src="https://img.shields.io/badge/Apache%20Tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=black" alt="Tomcat">
<img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black" alt="Render">

---

## 🏆 Achievements

- 🛡️ **DRDO PXE Chandipur** — Software Engineering Internship, Jun–Jul 2026 (Certificate No. 249/2026)
- 🤖 **Astro Vedangam** — Software Development Internship, Sep 2025 – Jan 2026
- 🇮🇳 **Smart India Hackathon 2024** — built a working prototype for *"Let's Learn Constitution – Citizen Perspective"*
- 📜 **NPTEL Elite** — *Data Structures & Algorithms using Java* (2024) · *Programming in Java* (2025)
- 🛰️ **IIRS-ISRO** — *Geo-data Sharing & Cyber Security* (2024), Grade A+

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&hide_border=true&rank_icon=github&theme=transparent" height="165" alt="GitHub stats">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_GITHUB_USERNAME&hide_border=true&theme=transparent" height="165" alt="GitHub streak">
</p>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME&layout=compact&hide_border=true&theme=transparent" height="140" alt="Top languages">
</p>

---

## 🧠 Currently Exploring

```text
Spring Boot & Backend Architecture
        ↓
System Design & Distributed Systems
        ↓
Real-Time Communication & Networking
        ↓
LLM Agents & Retrieval Workflows
        ↓
Production-Ready Full-Stack Systems
```

---

## 🤝 Let's Connect

I'm open to internships, full-time roles and collaborations in backend, real-time systems and applied AI.

<p align="center">
  <a href="https://github.com/YOUR_GITHUB_USERNAME">GitHub</a>
  ·
  <a href="https://www.linkedin.com/in/YOUR_LINKEDIN_USERNAME/">LinkedIn</a>
  ·
  <a href="https://sonuray.dev">Portfolio</a>
  ·
  <a href="mailto:raysonu0900@gmail.com">Email</a>
</p>

<p align="center">
  <sub>Crafting Code. Creating Impact.</sub>
</p>
