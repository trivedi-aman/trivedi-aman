# Hi, I'm Aman Trivedi 👋

**Software Engineer · GenAI & ML Systems · Data Platforms**

I build production systems where software engineering meets machine learning:
multi-agent LLM platforms, voice agents, credit-risk models, and data pipelines.
Currently building internal tools and ML systems in fintech.

🌐 **[amantrivedi.com](https://www.amantrivedi.com)** has all my projects, articles and labs.

---

### 📦 Open source

**[misheard](https://github.com/trivedi-aman/misheard)** · [PyPI](https://pypi.org/project/misheard/)

Python library that matches Indian names and places by how they **sound**, across Roman, Devanagari and Tamil script.
It knows retroflex sounds, Hindi schwa deletion, Tamil voicing and regional confusions (v/b, ड़/r), handles titles,
initials and word order, and explains every match. Pure Python, no dependencies. Extracted from Vaani.

```bash
pip install misheard
```

```python
from misheard import distance, Matcher

distance("Barmer", "बाड़मेर")   # 0.4  same place
distance("Mohan", "Rohan")       # 1.7  different people
Matcher(districts).best_match("Baadmer")
```

---

### 🚀 Featured projects

| Project | What it does | Stack |
|---|---|---|
| **Agentic Support Platform** | Multi-tenant async customer support with RAG, vision, action and escalation agents | LangGraph, FastAPI, RAG |
| **[Vaani](https://github.com/trivedi-aman/vaani)** | Multilingual voice agent for lending support, with sound-based name matching ([misheard](https://github.com/trivedi-aman/misheard)) and identity verification | Python, AWS, speech |
| **LoanRoute** | Loan applicant prioritization with explainable predictions | XGBoost, SHAP, FastAPI |
| **DataFlow** | Metadata-driven ETL that compiles YAML into DuckDB, Polars or Spark jobs | Python, DuckDB, Polars, Spark |
| **[StudyForge](https://github.com/trivedi-aman/studyforge)** | Document platform: RAG chat, YouTube-to-notes, text-to-slides | Groq, NVIDIA NIM, RAG |
| **Vintage ML Compressor** | Audio plugin with C++ DSP and an ML settings recommender | C++, JUCE |

**In production at work:** live operations KPI dashboard (React + FastAPI + PostgreSQL),
multi-agent policy assistant with guardrails, an XGBoost collections-prioritization model,
and an HR system for attendance, leave and hiring (web + Android app).

---

### 🧰 Tech stack

- **Languages:** Python · C++ · SQL · JavaScript/TypeScript
- **GenAI:** LangGraph · RAG · AWS Bedrock (AgentCore) · Strands Agents · Groq · NVIDIA NIM
- **ML:** XGBoost · scikit-learn · SHAP · credit scorecards (WOE/IV) · survival & causal analysis
- **Backend:** FastAPI · SQLAlchemy · Alembic · PostgreSQL · React
- **Mobile:** Flutter (Android)
- **Data:** Spark/PySpark · Polars · DuckDB · Airflow
- **Cloud & tools:** AWS (EC2, Bedrock) · Cloudflare · Docker · Git · Linux

---

### ✍️ Recent writing ([all articles →](https://www.amantrivedi.com))
- Fixing a slow dashboard: N+1 queries and missing indexes
- Designing RAG for policy documents
- How a voice agent handles names, dates and numbers
- Running Airflow with LocalExecutor on a single EC2 instance

---

### 📫 Connect
[Website](https://www.amantrivedi.com) · [LinkedIn](https://linkedin.com/in/aman-trivedi29) · [LeetCode](https://leetcode.com/u/amantrivedi2003) · [HackerRank](https://hackerrank.com/profile/amantrivedi2003)
