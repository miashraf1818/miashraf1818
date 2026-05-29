<!--
═══════════════════════════════════════════════════════════════════════════
  MOHAMMED IKRAM ASHRAFI · GitHub profile README
  File:   README.md  in  github.com/miashraf1818/miashraf1818
═══════════════════════════════════════════════════════════════════════════
-->

<a href="https://www.mohammed-ikram-ashrafi.in/">
  <img width="100%" alt="Mohammed Ikram Ashrafi — Python · GenAI · RAG Engineer"
       src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,16,24&height=220&section=header&text=Mohammed%20Ikram%20Ashrafi&fontSize=46&fontColor=ffffff&fontAlignY=38&desc=Python%20%C2%B7%20GenAI%20%C2%B7%20RAG%20Engineer&descSize=18&descAlignY=58&animation=fadeIn" />
</a>

<div align="center">

<a href="https://www.mohammed-ikram-ashrafi.in/">
  <img alt="What I do — typing animation"
       src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2800&pause=900&color=A78BFA&center=true&vCenter=true&width=760&lines=Python+%C2%B7+GenAI+%C2%B7+RAG+Engineer;Building+EchoVault+AI+%E2%80%94+memory+intelligence;FastAPI+%C2%B7+LangChain+%C2%B7+Qdrant+%C2%B7+LLaMA-3;Privacy-first+%E2%80%94+grounded+%E2%80%94+cited;A+companion%2C+not+a+clone." />
</a>

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-mohammed--ikram--ashrafi.in-0B0B0F?style=for-the-badge&logo=vercel&logoColor=white&labelColor=0B0B0F)](https://www.mohammed-ikram-ashrafi.in/)
[![EchoVault AI](https://img.shields.io/badge/EchoVault_AI-echovaultai.me-7C3AED?style=for-the-badge&logoColor=white)](https://echovaultai.me)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-mohammed--ikram--ashrafi-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohammed-ikram-ashrafi/)
[![Email](https://img.shields.io/badge/Email-ikramshariff2005-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ikramshariff2005@gmail.com)

<br/>

<img src="https://komarev.com/ghpvc/?username=miashraf1818&label=PROFILE+VIEWS&color=7C3AED&style=flat-square" />
<img src="https://img.shields.io/github/followers/miashraf1818?label=FOLLOWERS&style=flat-square&color=7C3AED&labelColor=0d1117" />
<img src="https://img.shields.io/github/stars/miashraf1818?label=STARS&style=flat-square&color=A78BFA&labelColor=0d1117" />

</div>

---

## ` whoami `

> Building production AI systems that ship — not demos that crash.
> Currently shipping **EchoVault AI**: privacy-first emotional memory intelligence with grounded retrieval and cited reflections.

```python
class MohammedIkram:
    role        = "Python Full-Stack Developer · GenAI Engineer"
    location    = "India · open to remote, worldwide"
    flagship    = "EchoVault AI — memory intelligence with grounded retrieval"
    obsessed    = ("Temporal Emotional RAG", "vector retrieval", "production reliability")
    philosophy  = "A companion, not a clone."

    stack = {
        "ai":        ["LangChain", "RAG", "Qdrant", "Pinecone", "BGE", "Groq", "LLaMA-3"],
        "backend":   ["FastAPI", "Django", "DRF", "Flask", "Async Python"],
        "frontend":  ["React 19", "TanStack Start", "Next.js", "Tailwind"],
        "data":      ["PostgreSQL", "MongoDB", "SQLite"],
        "infra":     ["Docker", "AWS EC2", "Vercel", "Render", "Nginx", "GH Actions"],
    }

    def what_im_doing_now(self):
        return [
            "shipping EchoVault AI — temporal emotional RAG, live at echovaultai.me",
            "phase 1: Clerk auth + per-user Qdrant namespaces + managed Postgres",
            "open to Python / AI Engineer roles — remote or India-based",
        ]
```

---

## 🚀 Flagship — EchoVault AI

<table>
<tr>
<td width="55%" valign="top">

**Reflective memory intelligence platform.**
Temporal Emotional RAG that chunks by feeling, embeds per-user vector spaces, and answers grounded — every claim cited, no impersonation.

- 📥 Ingests WhatsApp exports, journals, voice notes
- 🧩 Chunks by **emotion + time**, not tokens
- 🔐 Per-user Qdrant namespaces · AES-256 encrypted vault
- 🎯 Grounding Validator drops claims under **0.7 confidence**
- ⚡ End-to-end pipeline runs in **~1.91s** for a 5MB upload
- 🧪 **124** backend tests · **11** property-based invariants

[![Live](https://img.shields.io/badge/Live-echovaultai.me-7C3AED?style=for-the-badge)](https://echovaultai.me)
[![Try Demo](https://img.shields.io/badge/Try_Demo-Live_RAG-059669?style=for-the-badge)](https://echovaultai.me/demo)
[![Case Study](https://img.shields.io/badge/Case_Study-Read-0B0B0F?style=for-the-badge)](https://www.mohammed-ikram-ashrafi.in/projects/echovault-ai)
[![Frontend](https://img.shields.io/badge/Frontend-Repo-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/miashraf1818/echo-vault-intelligence)
[![Backend](https://img.shields.io/badge/Backend-Repo-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/miashraf1818/echovault-backend-demo)

</td>
<td width="45%" valign="top">

<a href="https://echovaultai.me">
  <img width="100%" alt="EchoVault AI hero"
       src="https://raw.githubusercontent.com/miashraf1818/Portfolio/main/public/projects/echovault/echovault-hero.png" />
</a>

</td>
</tr>
</table>

### 🧬 The pipeline

```
WhatsApp .txt   ─┐
journal entries ─┼─→ Parser → Temporal Chunker → Emotional Enricher
voice note      ─┘                                 │ (Groq · LLaMA-3)
                                                   ↓
                          Embedder (BGE-small-en-v1.5, 384-dim)
                                                   ↓
                          Qdrant vector store + SQLite metadata
                                                   ↓
user query ──→ Hybrid retrieval ──→ Reflection Engine
                                                   ↓
                                       Grounding Validator
                                       (drops claims < 0.7 confidence)
                                                   ↓
                                  answer + cited memory chunks
```

---

## 🛠 Tech arsenal

<div align="center">

**Languages & Backend**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-A30000?style=for-the-badge&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

**AI · RAG · Vector**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21F?style=for-the-badge&logo=huggingface&logoColor=black)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logoColor=white)
![LLaMA-3](https://img.shields.io/badge/LLaMA--3-7289DA?style=for-the-badge&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TanStack](https://img.shields.io/badge/TanStack_Start-FF4154?style=for-the-badge&logo=react-query&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**Data & Infra**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)

</div>

---

## 📈 GitHub activity

<div align="center">

<img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=miashraf1818&theme=tokyonight" />
<img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=miashraf1818&theme=tokyonight" />

<br/>

<img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=miashraf1818&theme=tokyonight" />
<img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=miashraf1818&theme=tokyonight" />

<br/>

<img src="https://streak-stats.demolab.com?user=miashraf1818&theme=tokyonight&hide_border=true&background=0d1117&ring=A78BFA&fire=A78BFA&currStreakLabel=A78BFA" />

</div>

### 🐍 Watch the snake eat my contributions

<picture>
  <source media="(prefers-color-scheme: dark)"
          srcset="https://raw.githubusercontent.com/miashraf1818/miashraf1818/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)"
          srcset="https://raw.githubusercontent.com/miashraf1818/miashraf1818/output/github-snake.svg" />
  <img alt="snake eating my contribution graph"
       src="https://raw.githubusercontent.com/miashraf1818/miashraf1818/output/github-snake.svg" />
</picture>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=miashraf1818&bg_color=0d1117&color=A78BFA&line=7C3AED&point=ffffff&hide_border=true&theme=tokyo-night&area=true" />

</div>

---

## 🧱 Selected projects

| | Project | Stack | Status |
|:-:|---|---|:-:|
| 🧠 | **[EchoVault AI](https://echovaultai.me)** — Temporal Emotional RAG, grounded reflections | FastAPI · Qdrant · Groq · LLaMA-3 · React | Live |
| 🤖 | **[GenAI RAG Chatbot](https://github.com/miashraf1818/genai-rag-chatbot)** — sub-200ms Llama 3.3-70B, JWT + OAuth, multi-format ingestion | FastAPI · LangChain · Pinecone · Llama 3.3 | Production |
| 🛡 | **[Anti-Ragging Platform](https://github.com/miashraf1818/antiragging-backend)** — RBAC, real-time notifications, evidence tracking | Django · DRF · React · Postgres | Production |

---

## 🧭 Currently leveling up

```text
Advanced RAG optimization        ████████░░  80%
AI infrastructure engineering    ███████░░░  70%
Distributed backend systems      ██████░░░░  60%
AWS cloud architecture           █████░░░░░  50%
High-performance async Python    ████████░░  80%
```

---

## 🪞 Philosophy

> *"I'd rather ship one boring RAG pipeline that runs at 3 AM than a hundred Jupyter notebooks that only work on my laptop."*

|  🛡 Ethical AI  |  🔒 Privacy-first  |  📐 Scalable  |  🫂 Human-centered  |
|:---:|:---:|:---:|:---:|
| Building responsibly | Zero surveillance | Long-term architecture | AI for humans, not against them |

---

<div align="center">

### Let's build something that ships.

[![LinkedIn](https://img.shields.io/badge/Connect-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohammed-ikram-ashrafi/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-0B0B0F?style=for-the-badge&logo=vercel&logoColor=white)](https://www.mohammed-ikram-ashrafi.in/)
[![Email](https://img.shields.io/badge/Email-Drop_a_line-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ikramshariff2005@gmail.com)
[![EchoVault](https://img.shields.io/badge/Try-EchoVault_AI-7C3AED?style=for-the-badge)](https://echovaultai.me)

<sub>*Open to Python / AI Engineer roles, freelance work, and collaborations on intelligent products.*</sub>

</div>

<img width="100%"
     src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,16,24&height=120&section=footer&animation=fadeIn" />
