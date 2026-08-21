<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Sania%20Khizar&fontSize=42&fontColor=ffffff&animation=fadeIn&desc=Building%20GenAI%20Systems%2C%20One%20Deployed%20Project%20at%20a%20Time&descAlignY=68&descSize=16" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=3000&pause=800&color=A78BFA&center=true&vCenter=true&width=600&lines=Undergraduate+AI%2FCS+Student;Building+Practical+GenAI+Projects;LLM+Agents+%7C+RAG+Systems+%7C+Automation;Learning+by+Shipping%2C+Not+Just+Studying" alt="Typing SVG" />
</a>

<br/>

![Student](https://img.shields.io/badge/Status-AI%2FCS%20Undergraduate-6D28D9?style=for-the-badge)
![Location](https://img.shields.io/badge/Location-Pakistan-4C1D95?style=for-the-badge&logo=googlemaps&logoColor=white)

<br/>

[![Portfolio](https://img.shields.io/badge/Live%20Projects-7C3AED?style=for-the-badge&logo=streamlit&logoColor=white)](https://github.com/SaniaKhizar)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-5B21B6?style=for-the-badge&logo=linkedin&logoColor=white)](#)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-4C1D95?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SaniaKhizar)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=SaniaKhizar&color=7c3aed&style=for-the-badge&label=PROFILE+VIEWS)
![Followers](https://img.shields.io/github/followers/SaniaKhizar?style=for-the-badge&color=6d28d9&labelColor=1e1b2e)
![Stars](https://img.shields.io/github/stars/SaniaKhizar?style=for-the-badge&color=8b5cf6&labelColor=1e1b2e)

</div>

<br/>

## About Me

I'm an undergraduate AI/CS student spending summer break building a portfolio of **real, deployed GenAI systems** — not tutorial clones. My approach: pick a hard practical problem, build it file-by-file, break it, fix it, and document the actual bugs I hit instead of pretending everything worked on the first try.

I'm not claiming deep expertise I don't have yet — I'm early in DL/GenAI foundations and learning fast through building. What I *can* show: three projects that are live, working, and honestly documented, including the architecture decisions and trade-offs behind them.

```yaml
🔭 Currently Building:   Exploring next GenAI skill gap (post-agents, post-RAG)
🌱 Currently Learning:   Deep learning foundations, GenAI system design
🐛 Debugging Philosophy: Silent failures are the dangerous kind — always verify actual response structure
💬 Ask Me About:         LLM agents, RAG pipelines, GitHub Actions automation
📫 Open To:              Internships, collaboration, and honest feedback
```

<br/>

## Tech Stack

<div align="center">

**Languages & Core**

![Python](https://img.shields.io/badge/Python-14354C?style=flat-square&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**GenAI / ML**

![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logo=groq&logoColor=white)
![OpenRouter](https://img.shields.io/badge/OpenRouter-6D28D9?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-4C1D95?style=flat-square)
![scikit--learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square&logo=google&logoColor=white)

**Backend & Deployment**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

</div>

<br/>

## GenAI Skills Snapshot

| Domain | Proficiency | Details |
|---|:---:|---|
| **LLM Agents** | 🟣🟣🟣🟣⚪ | Function calling, tool use, conversation memory (Groq + Tavily) |
| **RAG Systems** | 🟣🟣🟣🟣⚪ | Chunking strategies, vector search (ChromaDB), relevance filtering |
| **API Automation** | 🟣🟣🟣🟣🟣 | Multi-model fallback chains, GraphQL integration, CI/CD via cron |
| **Computer Vision (Classical ML)** | 🟣🟣🟣⚪⚪ | Hand landmark features + Random Forest, self-collected datasets |
| **Deep Learning Foundations** | 🟣⚪⚪⚪⚪ | Actively learning — next focus area |

<br/>

## Featured Projects

<details>
<summary><b>🔎 AI Research Agent</b> — Conversational agent with live web search</summary>
<br/>

A GenAI agent that combines Groq-hosted LLMs with real-time web search (Tavily) via function calling, with conversation memory and a Streamlit interface. Built with a modular four-file architecture separating the LLM client, tools, agent logic, and GUI.

| | |
|---|---|
| **Live Demo** | [ai-research-agent-skh.streamlit.app](https://ai-research-agent-skh.streamlit.app) |
| **Stack** | Python, Groq, Tavily API, Streamlit |
| **Architecture** | `llm_client.py` → `tools.py` → `agent.py` → `gui.py` |
| **Repository** | [AI-research-agent](https://github.com/SaniaKhizar/AI-research-agent) |

</details>

<details>
<summary><b>📮 Automated LinkedIn Post Agent</b> — Fully autonomous content pipeline</summary>
<br/>

Scrapes AI/ML trends via GNews, generates posts through an OpenRouter multi-model fallback chain, and auto-publishes via the Buffer GraphQL API — running on a GitHub Actions cron schedule (Mon/Wed/Fri) with zero manual review.

| | |
|---|---|
| **Status** | 🟢 Live since Aug 2026 |
| **Stack** | Python, GNews API, OpenRouter, Buffer GraphQL API, GitHub Actions |
| **Real Bug Fixed** | Buffer's GraphQL union-type response was silently reporting false success — now correctly validated |
| **Real Bug Fixed** | `.gitignore` conflict broke CI commits — resolved with re-tracking + `git pull --rebase` |
| **Repository** | [daily-linkedIn-post-agent](https://github.com/SaniaKhizar/daily-linkedIn-post-agent) |

</details>

<details>
<summary><b>📚 RAG From Scratch</b> — Retrieval-augmented generation, built layer by layer</summary>
<br/>

A complete RAG pipeline built from the ground up: three chunking strategies (fixed-size, paragraph, sentence), ChromaDB vector store, Groq-backed LLM client, and dual interfaces — a Streamlit chat GUI and a FastAPI backend with Swagger docs — sharing a single pipeline instance.

| | |
|---|---|
| **Live Demo** | [rag-from-scratch-skh.streamlit.app](https://rag-from-scratch-skh.streamlit.app) |
| **Stack** | Python, ChromaDB, Groq, Streamlit, FastAPI |
| **Real Bug Fixed** | Heading-only orphan chunks polluting retrieval |
| **Real Bug Fixed** | Chat history duplication — resolved with stable IDs + activity counter |
| **Repository** | [rag-from-scratch](https://github.com/SaniaKhizar/rag-from-scratch) |

</details>

<details>
<summary><b>✋ GestureIQ — Rock Paper Scissors</b> — Real-time gesture classification</summary>
<br/>

Real-time rock-paper-scissors classifier using MediaPipe hand landmarks and a Random Forest model trained on a self-collected, 2,100-sample dataset.

| | |
|---|---|
| **Status** | 🟡 Model complete — web deployment in progress |
| **Stack** | Python, MediaPipe, scikit-learn |
| **Engineering Note** | Exploring the right web-deployment path without heavy client-side JS plumbing |
| **Repository** | [rock-paper-scissor](https://github.com/SaniaKhizar/rock-paper-scissor) |

</details>

<br/>

## GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=SaniaKhizar&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=8b5cf6&text_color=c9d1d9" width="48%"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=SaniaKhizar&theme=tokyonight&hide_border=true&background=0d1117&ring=8b5cf6&fire=a78bfa&currStreakLabel=a78bfa" width="48%"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SaniaKhizar&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&text_color=c9d1d9" width="40%"/>

</div>

<br/>

## Contribution Activity

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=SaniaKhizar&theme=tokyo-night&hide_border=true&bg_color=0d1117&color=a78bfa&line=8b5cf6&point=c9d1d9" width="90%"/>
</div>

<!-- SNAKE_START -->
<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/SaniaKhizar/SaniaKhizar/output/github-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/SaniaKhizar/SaniaKhizar/output/github-snake.svg"/>
  <img alt="GitHub Contribution Snake" src="https://raw.githubusercontent.com/SaniaKhizar/SaniaKhizar/output/github-snake.svg"/>
</picture>
</div>
<!-- SNAKE_END -->

<br/>

## Connect

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-6D28D9?style=for-the-badge&logo=gmail&logoColor=white)](#)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-4C1D95?style=for-the-badge&logo=linkedin&logoColor=white)](#)
[![GitHub](https://img.shields.io/badge/GitHub-1e1b2e?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SaniaKhizar)

*"Deployed and honestly documented beats polished and untested."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

</div>
