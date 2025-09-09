---
layout: default
title: Home
---

# Amber Hart — Class Projects

Hi! I’m Amber, a Cloud Security Architect & MBA student.  
This site highlights selected **course projects** and **experiments**. Each card links to the GitHub repo and a short write-up/demo if available.

---

## Projects

### 1) Cloud Security Chatbot
**What it is:**  Modern cloud security operations teams juggle multiple environments, tickets, and configuration details. Our Cloud Security Support Bot addresses the pain of repeatedly asking “What’s my subscription ID?”, “Which storage account did I reference?”, or “What steps did we take to resolve that alert last week?” By embedding a lightweight memory layer into an LLM‐powered chatbot, we enable operators to retrieve environment facts and past resolutions instantly—saving time and reducing context‐switching overhead.
**Tech:** Python, Streamlit, OpenAI, vector store  
**Highlights:** Memory for tenant/subscription context, tool-calling for KB search  
**Links:** [Report](/assets/reports/AHart Chatbot Report.pdf) · [Repo](https://github.com/amberhart01/cloudsecurity_chatbot)

<video controls width="720" poster="https://amberhart01.github.io/amberhart01/assets/images/snapshot_chatbot.jpeg">
  <source src="https://amberhart01.github.io/amberhart01/assets/videos/Cloud Chatbot.mp4" type="video/mp4">
  <!-- Optional fallback -->
  Your browser doesn’t support HTML5 video. Here’s a <a href="https://amberhart01.github.io/amberhart01/assets/videos/Cloud Chatbot.mp4">direct link</a>.
</video>
---

### 2) Compliance Advisor Chatbot
**What it is:** The Compliance Advisor Chatbot is a specialized AI assistant built to help organizations compare their internal security policies against the NIST SP 800-53 standard. It lives in the domain of cybersecurity and compliance, a critical area for any organization running regulated workloads in public clouds.  
**Tech:** LangChain, Python, Streamlit, OpenAI, Chromadb 
**Highlights:** Agentic AI workflow for policy-to-NIST control mapping, vector-based retrieval of internal documents, automated compliance gap analysis with explainable results, and an interactive Streamlit interface for security/compliance teams. 
**Links:** [Report](/assets/reports/AHart Domain Specific AI Report.pdf) · [Repo](https://github.com/amberhart01/compliance-advisor-chatbot)

<video controls width="720" poster="https://amberhart01.github.io/amberhart01/assets/images/assets/images/Convert to GIF project.jpeg">
  <source src="https://amberhart01.github.io/amberhart01/assets/videos/domainspecificAI.mp4" type="video/mp4">
  <!-- Optional fallback -->
  Your browser doesn’t support HTML5 video. Here’s a <a href="https://amberhart01.github.io/amberhart01/assets/videos/domainspecificAI.mp4">direct link</a>.
</video>

<video controls width="720" poster="https://amberhart01.github.io/amberhart01/assets/images/assets/images/Convert to GIF project.jpeg">
  <source src="https://amberhart01.github.io/amberhart01/assets/videos/domainspecificAI2.mp4" type="video/mp4">
  <!-- Optional fallback -->
  Your browser doesn’t support HTML5 video. Here’s a <a href="https://amberhart01.github.io/amberhart01/assets/videos/domainspecificAI2.mp4">direct link</a>.
</video>
---

### 3) RiskShield (In-Progress)
**What it is:** LLM-assisted control mapping and gap analysis with retrieval over policy docs.  
**Tech:** Python, FastAPI, LangChain, Azure OpenAI, Chromadb  
**Highlights:** RAG pipeline, eval prompts, report export  
**Links:** [Repo](https://github.com/amberhart01/RiskShield_Project7)

---
### 4) Synchronizing Cyber and Political Events Across Nations 
**What it is:** Three Minute Thesis: Exploring Cyber Threat Patterns as Predictive Indicators of Geopolitical Crises 
**Tech:** SQL, BigQuery, Looker Studio  
**Highlights:** Geo joins, performance tuning, drill-downs  
**Links:** [Report](/assets/reports/AHart_ThreeMinuteThesis_Report.pdf)

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vTTmTpqm-IfWYgqKb5VyLsOd_hepFG9uLkljGhFKenSsNj0Y22vD3bj9bMkrbdnHA/pubembed?start=false&loop=false&delayms=3000" 
        frameborder="0" width="720" height="420" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true">
</iframe>



---

## About
Cloud Security Architect focused on **DevSecOps, CSPM, and AI for security**. Currently pursuing an MBA (AI Business Innovation).

- 📫 Contact: amberhart01@outlook.com 
- 🔗 GitHub: [@amberhart01](https://github.com/amberhart01) · [LinkedIn:](https://linkedin.com/in/amber-s-hart) 
- [📄 Resume](https://github.com/amberhart01/amberhart01/blob/main/Amber_Resume_2025.pdf)

---

### How this site works
This portfolio uses **GitHub Pages + Jekyll (Cayman theme)**.  
- Edit site settings in `_config.yml`.  
- Add/organize content here in `index.md`.  
- Create new pages (e.g., `/about.md`, `/projects.md`) if you want a multi-page site.

_Last updated: {{ site.time | date: "%Y-%m-%d" }}_
