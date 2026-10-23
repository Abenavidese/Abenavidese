<div align="center">

<img src="assets/header.svg" alt="Anthony Benavides — AI Engineer · Full-Stack Developer · Web3 Builder" width="100%"/>

<a href="https://github.com/Abenavidese">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3200&pause=900&color=22D3EE&center=true&vCenter=true&width=720&lines=I+ship+AI+that+reaches+real+users;RAG+%2B+agents+with+evals%2C+not+vibes;Computer+vision+for+dental+diagnosis;Microservice+ERPs+running+in+production;Let's+build+something+awesome+together+%F0%9F%9A%80" alt="Typing intro"/>
</a>

<p>
  <img src="https://img.shields.io/badge/📍_Cuenca,_Ecuador-0b1020?style=for-the-badge" alt="Location"/>
  <img src="https://img.shields.io/badge/Open_to-Remote_roles-22d3ee?style=for-the-badge&labelColor=0b1020" alt="Open to remote roles"/>
  <img src="https://img.shields.io/badge/🎓_BEng-Computer_Science-818cf8?style=for-the-badge&labelColor=0b1020" alt="BEng Computer Science"/>
  <img src="https://komarev.com/ghpvc/?username=Abenavidese&style=for-the-badge&color=f472b6&label=PROFILE+VIEWS" alt="Profile views"/>
</p>

</div>

---

## 🧭 About me

```python
class Anthony:
    location   = "Cuenca, Ecuador 🇪🇨"
    degree     = "BEng Computer Science @ Universidad Politécnica Salesiana (2026)"
    focus      = ["LLM systems", "RAG & agents", "Computer vision", "Backend / microservices"]
    shipped    = {
        "dental_ai":  "Tooth segmentation + ICDAS classifier used by real dentists",
        "pandora":    "Multi-tenant ERP in production for 5 companies",
        "aether":     "Multi-tenant RAG + agent swarm with eval-driven development",
    }
    community  = "ETH Ecuador core team 🌐"
    learning   = "AWS Machine Learning Engineer Associate"
    fun_fact   = "full stack dev & ceviche lover 🍤"

    def motto(self):
        return "Measure it, test it, ship it."
```

<div align="center">
  <img src="assets/journey.svg" alt="Journey timeline: UPS internship, ETIKOS internship, freelance, BEng, F.S.O. Group / Pandora" width="100%"/>
</div>

---

## 🚀 Featured work

<table>
<tr>
<td width="50%" valign="top">

### 🤖 [Aether-ITSM](https://github.com/Abenavidese/Aether-ITSM)
**Multi-tenant AI service desk** · Nebius × NVIDIA hackathon

LangGraph agent swarm + hybrid RAG (pgvector HNSW + BM25 + exact IDs + multilingual reranker), Postgres row-level security, vision on screenshots, cost and p50/p95 latency tracing, red-team script and CI.

`Python` `LangGraph` `pgvector` `FastAPI` `Ollama` `GitHub Actions`

</td>
<td width="50%" valign="top">

### 🦷 ICDAS Dental AI · *CEDIA / UPS research*
**Computer vision in clinical use**

Trained the tooth **segmentation model** that feeds a cascade and the **ICDAS caries classifier**. Gathered requirements and defined the labeling directly with dentists, then iterated on post-launch feedback.

`PyTorch` `Segmentation` `Classification` `LoRA` · *private*

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧾 Pandora ERP · *F.S.O. Group*
**From zero to production in ~6 months**

Top backend contributor of a ~20-microservice ERP: electronic invoicing (SRI), accounting, treasury, payroll, withholdings and purchasing. Live for 5 companies, with Jest test suites.

`NestJS` `PostgreSQL` `Redis` `Supabase` `Render` · *private*

</td>
<td width="50%" valign="top">

### 🛡️ [EqualPass Identity](https://github.com/Abenavidese/EqualPass-Identity) & [Rayls Shield](https://github.com/Abenavidese/rayls-shield-BA)
**Privacy-first Web3 hackathon builds**

Fraud-proof student verification for LATAM with zero-knowledge proofs, biometric device checks and soulbound NFTs on Polkadot.

`TypeScript` `Solidity` `ZK proofs` `Polkadot`

🏆 Aleph hackathon winner · 🥈 Rayls hackathon 2nd place

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📚 [Library Management System](https://github.com/Abenavidese/ProyectoIntegradorAB)
**Full-stack university integrator project**

Angular 17 frontend (loans, reservations, returns, reports) with a JWT interceptor, plus a [Jakarta EE backend](https://github.com/Abenavidese/ProyectoJakarataEE) (JAX-RS, JPA, EJB, WildFly, roles).

`Angular` `Java` `Jakarta EE` `JWT`

</td>
<td width="50%" valign="top">

### ⚡ [CUDA & Vision Labs](https://github.com/Abenavidese/CUDA-Parallel-Computing)
**GPU computing and classic CV**

CPU vs GPU [filter benchmarks](https://github.com/Abenavidese/filter-performance-cpu-gpu), [super-resolution + object detection benchmark](https://github.com/Abenavidese/cv-superres-objectdetection-benchmark) and [CUDA image labs](https://github.com/Abenavidese/cuda-image-labs).

`C++` `CUDA` `OpenCV` `MPI`

</td>
</tr>
</table>

<details>
<summary><b>📊 Aether-ITSM eval results (click to expand)</b></summary>
<br/>

Retrieval quality over a 74-query evaluation set, baseline → final system:

| Metric | Baseline | Final |
|:--|:--:|:--:|
| hit@1 | 0.625 | **0.938** |
| hit@5 | 0.781 | **0.984** |
| MRR | 0.689 | **0.961** |
| nDCG@5 | 0.709 | **0.957** |
| Correct "no answer" | 0.20 | **0.80** |
| Cross-tenant leaks | — | **0** |

Agent safety: 42 ticket scenarios + 10 concierge cases, **0 unsafe actions** · **287 tests** passing.

</details>

---

## 🛠️ Tech stack

<div align="center">

**🧠 AI / ML**<br/>
<img src="https://skillicons.dev/icons?i=python,pytorch,opencv&theme=dark" alt="AI and ML"/>
<br/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain"/>
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white" alt="LangGraph"/>
<img src="https://img.shields.io/badge/RAG-pgvector-336791?style=flat-square&logo=postgresql&logoColor=white" alt="RAG pgvector"/>
<img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" alt="Ollama"/>
<img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA"/>

**⚙️ Backend & Data**<br/>
<img src="https://skillicons.dev/icons?i=nodejs,nestjs,fastapi,java,postgres,redis,supabase&theme=dark" alt="Backend"/>

**🎨 Frontend**<br/>
<img src="https://skillicons.dev/icons?i=ts,react,nextjs,angular,tailwind,html,css&theme=dark" alt="Frontend"/>

**☁️ DevOps & Web3**<br/>
<img src="https://skillicons.dev/icons?i=docker,githubactions,aws,gcp,git,linux,solidity&theme=dark" alt="DevOps and Web3"/>

</div>

---

## 📈 GitHub activity

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Abenavidese&show_icons=true&hide_border=true&bg_color=0b1020&title_color=22d3ee&icon_color=818cf8&text_color=e2e8f0&count_private=true" alt="GitHub stats"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Abenavidese&layout=compact&hide_border=true&bg_color=0b1020&title_color=22d3ee&text_color=e2e8f0&langs_count=8&exclude_repo=enKrypt,hygiea,zket-core-program,eth-ecu-website" alt="Top languages"/>

<img src="https://streak-stats.demolab.com?user=Abenavidese&hide_border=true&background=0B1020&ring=818CF8&fire=F472B6&currStreakLabel=22D3EE&sideLabels=E2E8F0&dates=94A3B8&currStreakNum=F8FAFC&sideNums=F8FAFC" alt="Contribution streak" width="80%"/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Abenavidese/Abenavidese/output/github-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Abenavidese/Abenavidese/output/github-snake.svg"/>
  <img alt="Snake eating my contribution graph" src="https://raw.githubusercontent.com/Abenavidese/Abenavidese/output/github-snake.svg" width="100%"/>
</picture>

</div>

---

<div align="center">

### 🤝 Let's build something awesome together

Open to **AI Engineer**, **LLM Engineer** and **Full-Stack** roles, remote from LATAM.<br/>
Happy to talk about RAG evaluation, agents, computer vision or Web3. 🌎

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:22d3ee,50:818cf8,100:f472b6&height=110&section=footer" width="100%" alt="footer wave"/>

</div>
