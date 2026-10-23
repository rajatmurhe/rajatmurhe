<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b0d16,50:1f2a5c,100:8ea2ff&height=190&section=header&text=Rajat%20Murhe&fontSize=54&fontColor=ffffff&fontAlignY=36&desc=AI%20Engineer%20%C2%B7%20LLM%20Agents%20%C2%B7%20RAG%20%C2%B7%20Evals&descAlignY=58&descSize=18" width="100%" alt="Rajat Murhe banner"/>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=2800&pause=900&color=8EA2FF&center=true&vCenter=true&width=620&lines=I+build+AI+agents+that+are+safe+to+ship;Evals+first%2C+then+features;RAG%2C+LangGraph%2C+MCP%2C+FastAPI%2C+Next.js;Final+year+CS+(AI+%26+ML)+%40+VIT+Chennai" alt="Typing intro"/></a>

<p>
<a href="https://linkedin.com/in/rajat-murhe"><img src="https://img.shields.io/badge/LinkedIn-rajat--murhe-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:rajatmurhe1@gmail.com"><img src="https://img.shields.io/badge/Email-rajatmurhe1%40gmail.com-8EA2FF?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://drive.google.com/file/d/1hkfZVrAmDvxD9OvDVLowiNIKv6A7m7Fz/view?usp=sharing"><img src="https://img.shields.io/badge/Resume-View-111421?style=for-the-badge&logo=googledrive&logoColor=white" alt="Resume"/></a>
<img src="https://komarev.com/ghpvc/?username=rajatmurhe&style=for-the-badge&color=1f2a5c&label=Profile+views" alt="Profile views"/>
</p>

</div>

## About me

```yaml
name:        Rajat Murhe
based_in:    Pune, India
studying:    BTech Computer Science (AI and Machine Learning), VIT Chennai, graduating Sep 2027
experience:  3 internships across AI engineering, applied ML and AI product work
building:    LLM agents, RAG systems, eval harnesses, FastAPI backends, Next.js frontends
daily_tools: Claude Code, Cursor, Codex
looking_for: AI, GenAI and agentic AI internships and junior roles (India or remote)
```

I care about AI systems that are right, safe and fast at the same time. Most of my projects ship with an eval set, a red team set and CI that blocks regressions, because a demo that works once is not a product.

## Featured projects

<table>
<tr>
<td width="50%" valign="top">

### 📈 [TickerSage](https://github.com/rajatmurhe/tickersage)
Read only crypto market research agent.

- 7 tool integrations, every number checked by a **number verifier**: 100% of numbers traced to source on a blind held out eval
- Slowest 5% latency cut from **4.5 s to 1.7 s** at the same 78.8% pass rate
- Attacks getting through cut from **72.8% to 1.9%**, with 932 regression attacks blocked
- RAG MRR improved from **0.533 to 0.721**

`Python` `FastAPI` `LangGraph` `MCP` `pgvector` `Redis` `Next.js` `Claude` `OpenAI` `Groq`

</td>
<td width="50%" valign="top">

### 🩺 [ClinicVoice AI](https://github.com/rajatmurhe/clinicvoice-ai)
Voice first clinic receptionist in English, Hindi and Marathi.

- Six agents in **LangGraph** with MCP tools, where only the FAQ agent calls an LLM
- Real Google Calendar booking, Groq with Gemini failover, Amazon Bedrock as a second provider
- Global safety gate added after live testing; evals and red team run in CI
- Semantic caching cut average response time from **about 8.1 s to 48 ms** in project testing

`Python` `FastAPI` `LangGraph` `MCP` `Whisper` `XTTS v2` `Bedrock` `Docker`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📊 [Atlas](https://github.com/rajatmurhe/atlas-commercial-intelligence)
AI powered commercial intelligence workbench.

- 24,576 synthetic pharma sales records on a **PostgreSQL star schema**
- LangGraph analytics agent with SQL validation before any query runs
- Forecast MAPE of **1.25%** against 4.70% for a seasonal naive baseline
- 19 backend tests; Langfuse tracing in progress

`Python` `LangGraph` `PostgreSQL` `SQL` `Forecasting`

</td>
<td width="50%" valign="top">

### 📄 [ContractIQ](https://github.com/rajatmurhe/contractiq)
AI contract review assistant. [Live demo](https://contractiq-frontend-2e3u.onrender.com/)

- Ask questions about a contract in plain language
- Every answer shows the **exact source quote** it came from, checked against the contract text
- Synthetic evals for missing evidence, conflicting clauses and prompt injection

`Next.js` `TypeScript` `FastAPI` `SQLite` `Google Sign In` `Render`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎥 [FieldProof AI](https://github.com/rajatmurhe/fieldproof-ai)
Multi tenant video QA platform for field service.

- Gemini checks job videos against a configurable checklist
- PASS, FAIL or NOT_VISIBLE findings with **evidence timestamps** and human review
- PostgreSQL job queue with retries and stale job recovery

`Python` `FastAPI` `Next.js` `PostgreSQL` `Gemini` `Clerk`

</td>
<td width="50%" valign="top">

### 🛡️ [SentinelAI](https://github.com/rajatmurhe/Sentinel-AI)
Adaptive insider threat detection. [Live demo](https://sentinel-ai-czmu.onrender.com)

- 10 stage pipeline with Isolation Forest and One Class SVM
- **Tree SHAP** explains every flag
- Post quantum cryptography layer and multi turn attack simulations
- Research paper in progress

`Python` `FastAPI` `React` `Scikit-learn` `SHAP`

</td>
</tr>
</table>

<details>
<summary><b>More projects</b></summary>
<br>

| Project | What it is | Links |
|---|---|---|
| Pulse Outreach | Job application and multi resume routing platform | [GitHub](https://github.com/rajatmurhe/Job-Outreach-Platform) |
| AI Job Assistant | Resume and job matching with evidence for every skill | [GitHub](https://github.com/rajatmurhe/ai-job-assistant) |
| Market Signal | Prediction market terminal built on news sentiment | [Live](https://market-signal-kh9r.onrender.com) · [GitHub](https://github.com/rajatmurhe/Market-Signal) |
| NeuroAI | Explainable clinical diagnostic platform | [Live](https://neuroai-diagnostic-platform.onrender.com) · [GitHub](https://github.com/rajatmurhe/NeuroAI-Diagnostic-Platform) |
| RAG Intelligence | Full stack chat with PDFs platform | [Live](https://ragpdf-frontend.onrender.com) · [GitHub](https://github.com/rajatmurhe/RAGPDF) |
| CreditX | Credit risk classification | [Live](https://credix.streamlit.app) · [GitHub](https://github.com/rajatmurhe/CrediX-Explainable-Credit-Intelligence) |

</details>

## Experience

| Role | Company | When |
|---|---|---|
| AI Product Growth and Strategy Intern | DCS AI Technologies | Sep 2026 to Present |
| AI/ML Intern | Linkific (Remote) | Jun 2026 to Aug 2026 |
| AI Intern | Rungta Ventures AI | Jan 2026 to May 2026 |

- **DCS AI Technologies:** API integration, testing multimodal AI workflows and credit consumption, AI connector platform testing, debugging and documented test cases.
- **Linkific:** Secure enterprise AI assistant backend with FastAPI, RAG on PostgreSQL with pgvector, role based access control and Groq.
- **Rungta Ventures AI:** Worked on the Buddyly and MyCA platforms in a team of about ten, with NLTK and spaCy document validation and semantic search.

## Tech stack

**AI and agents**
<p>
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/MCP-111421?style=flat-square"/>
<img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white"/>
<img src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white"/>
<img src="https://img.shields.io/badge/Groq-F55036?style=flat-square"/>
<img src="https://img.shields.io/badge/Amazon%20Bedrock-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white"/>
<img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white"/>
</p>

**Backend and data**
<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/pgvector-336791?style=flat-square"/>
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/>
</p>

**Frontend and DevOps**
<p>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white"/>
<img src="https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white"/>
<img src="https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black"/>
</p>

## Certifications and achievements

- 🏆 **First Prize, AGRHINOVA Hackathon**, VIT Chennai
- 🎓 Avery Dennison Scholarship
- ☁️ AWS Certified Developer Associate · AWS Certified Cloud Practitioner
- ☁️ Google Cloud Professional Machine Learning Engineer
- ☁️ Microsoft Azure Developer Associate (AZ-204) · Azure Fundamentals (AZ-900) · ML Operations Engineer Associate
- 🤖 IBM Advanced Generative AI · Agile Fundamentals

## GitHub activity

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=rajatmurhe&bg_color=0b0d16&color=8ea2ff&line=8ea2ff&point=ffffff&area=true&area_color=1f2a5c&hide_border=true" width="100%" alt="Contribution graph"/>
</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:8ea2ff,50:1f2a5c,100:0b0d16&height=110&section=footer" width="100%" alt=""/>
</div>
