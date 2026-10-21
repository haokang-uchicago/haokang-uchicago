![Hao (Jeff) Kang - I build LLM agents that do real work: MCP tool servers, Agent Skills, Voice AI, data pipelines](https://raw.githubusercontent.com/kh1054901651-cloud/kh1054901651-cloud/main/banner-agent.png)

### AI Engineer · LLM Agents · Data Engineering — MS Applied Data Science, University of Chicago

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Hao%20(Jeff)%20Kang-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hao-kang-6654b5331/)
![UChicago](https://img.shields.io/badge/MS%20Applied%20Data%20Science-University%20of%20Chicago-800000?style=for-the-badge)
![UIUC](https://img.shields.io/badge/BS%20Economics%20%2B%20Statistics-UIUC-E84A27?style=for-the-badge)
![Location](https://img.shields.io/badge/Chicago%2C%20IL-424242?style=for-the-badge&logo=googlemaps&logoColor=white)
![Open to work](https://img.shields.io/badge/Open%20to%20work-2EA043?style=for-the-badge)
[![Email](https://img.shields.io/badge/haok%40uchicago.edu-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:haok@uchicago.edu)

I build LLM applications that do real work inside a company — agents that call tools safely, write the report, merge the spreadsheets, and know when to hand off to a human.

**Right now I'm a Merit Scholar in the University of Chicago's MS in Applied Data Science**, after a B.S. in Economics with a Statistics minor from the University of Illinois Urbana-Champaign (GPA 3.9/4.0, Dean's List, Data Science Certificate). This past summer I shipped MCP tool servers, agent Skills, and a full-stack LLM app as an AI Application Engineer intern at Beijing Energy Holding's IT arm. Before that: entity resolution over 200K+ medical-institution records, and churn modeling at McKinsey.

---

## What I've shipped

**Agent tool integration over MCP** — connected a company LLM assistant to WeCom calling through a Node.js MCP tool server, so employees start voice and video calls from chat, with a confirmation step that prevents mis-dials.

**AI meeting-minutes app (Vue 3 · Spring Boot · MySQL)** — turns raw notes into structured minutes through the Qwen LLM API, with human-in-the-loop review and role-based access.

**Agent Skills that replaced a manual monthly process** — two Python Skills that merge 8 business-unit Excel reports into one 256-project tracker and draft the Word report.

**Report-writing agent** — generates tech-intelligence and monthly policy reports from whitelisted sources into Word templates, builds the contents page automatically, and blocks weak drafts before they reach a reviewer.

**Entity resolution at scale** — cleaned and normalized 200K+ Chinese medical-institution records from 8 sources; found that 53–65% of records in every province were duplicates and merged them into canonical entities with a full ID-mapping audit trail.

**Churn-risk model at McKinsey** — XGBoost model that caught 42 vs. 27 churners in the top-10% contact list against the existing rule (5-fold CV AUC 0.98 ± 0.007), explained with SHAP, sized with break-even analysis, and paired with a powered A/B test design.

---

## Building now

**Xiaowu — voice AI companion agent** *(2-person team, on OpenClaw)* — speech in through Doubao ASR, an LLM that answers in a consistent persona using the user's memory, and TTS back out on mobile.

- Long-term memory with source tracing and user-controlled deletion, a 15-category user profile, and a persistent mood model — the LLM only sees the context each turn needs
- Permission-checked tools in a custom OpenClaw plugin (reminders, to-dos, alarms, check-ins, notes) with retries, timeouts and cancellation so nothing fires twice

---

## How I work

| Building agents | Working with data |
| --- | --- |
| Tool calling and MCP servers with confirm steps before anything irreversible | Text normalization, deduplication and entity resolution with an audit trail |
| Agent Skills that turn recurring manual work into one command | Leakage checks, cross-validation, and SHAP before anyone trusts a score |
| Memory designs that give the model only what it needs, and let users delete it | A/B tests designed with power analysis and intent-to-treat evaluation |
| Human-in-the-loop review wherever the output leaves the building | Clean data loaded into a warehouse, not left in a notebook |

---

## Stack

**LLM & Agents**

![MCP](https://img.shields.io/badge/MCP-111111?style=for-the-badge&logo=anthropic&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![OpenAI-compatible APIs](https://img.shields.io/badge/OpenAI--compatible%20APIs-412991?style=for-the-badge&logo=openai&logoColor=white)
![Qwen](https://img.shields.io/badge/Qwen-615CED?style=for-the-badge)
![DeepSeek](https://img.shields.io/badge/DeepSeek-4D6BFE?style=for-the-badge)
![Doubao](https://img.shields.io/badge/Doubao-1E6FFF?style=for-the-badge)
![OpenClaw](https://img.shields.io/badge/OpenClaw-E5484D?style=for-the-badge)
![ASR / TTS](https://img.shields.io/badge/ASR%20%2F%20TTS-0B6A0B?style=for-the-badge)

**ML & Analytics**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=for-the-badge)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)

**Engineering**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Vue 3](https://img.shields.io/badge/Vue%203-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## Education

**MS, Applied Data Science — University of Chicago** (2026 – 2027, Merit Scholarship)

**BS, Economics, Minor in Statistics — University of Illinois Urbana-Champaign** (2022 – 2026) · GPA 3.9/4.0 · Dean's List (top 5%) · Data Science Certificate

---

## Experience

**Beijing Energy Holding — Jingneng Information Technology** · AI Application Engineer Intern (2026) · **Beijing Health Online Technology** · Data Engineering Intern (2025) · **McKinsey & Company, Shanghai** · Business Analyst Intern (2024 – 2025)

Outside of code: four years as Administrative Director of the Jasmine Field Orchestra at UIUC — 10+ concerts, 1,000+ tickets sold, and $5K in brand sponsorships.
