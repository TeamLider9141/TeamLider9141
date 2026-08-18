<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4F46E5,50:7C3AED,100:A78BFA&height=210&section=header&text=John%20Uik&fontSize=54&fontColor=FFFFFF&animation=fadeIn&fontAlignY=36&desc=Software%20Engineer%20%C2%B7%20AI%20Engineer%20%C2%B7%20Product%20Builder&descSize=18&descAlignY=58" width="100%" alt="header"/>

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=24&duration=2800&pause=800&color=8B5CF6&center=true&vCenter=true&width=700&lines=Software+Engineer;AI+%2F+ML+%26+LLM+Systems+Engineer;Full+Stack+Developer;Local-First+AI+Tooling+Builder;Open+Source+Contributor" alt="typing-svg"/>

<br/>

<img src="https://img.shields.io/badge/Education-B.Sc._Computer_Science-6366F1?style=flat-square&logo=googlescholar&logoColor=white" alt="degree"/>
<img src="https://img.shields.io/badge/Focus-AI_%26_Distributed_Systems-7C3AED?style=flat-square&logo=openaigym&logoColor=white" alt="focus"/>
<img src="https://img.shields.io/badge/Location-Tashkent,_Uzbekistan-4F46E5?style=flat-square&logo=googlemaps&logoColor=white" alt="location"/>

<br/><br/>

<a href="https://teamlider9141.github.io"><img src="https://img.shields.io/badge/Portfolio-4F46E5?style=for-the-badge&logo=vercel&logoColor=white" alt="portfolio"/></a>
<a href="https://www.linkedin.com/in/johnuik"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin"/></a>
<a href="mailto:johnuik006@gmail.com"><img src="https://img.shields.io/badge/Email-7C3AED?style=for-the-badge&logo=gmail&logoColor=white" alt="email"/></a>
<a href="https://github.com/TeamLider9141"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="github"/></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=TeamLider9141&style=flat-square&color=6366f1&label=Profile+Views" alt="profile views"/>
<a href="https://github.com/TeamLider9141?tab=followers"><img src="https://img.shields.io/github/followers/TeamLider9141?style=flat-square&color=7C3AED&labelColor=0D1117&label=Followers" alt="followers"/></a>
<a href="https://github.com/TeamLider9141?tab=repositories"><img src="https://img.shields.io/github/stars/TeamLider9141?style=flat-square&color=8B5CF6&labelColor=0D1117&label=Stars" alt="stars"/></a>

</div>

---

## About

Software engineer focused on **AI systems, LLM infrastructure, and full stack product engineering**. I design and ship end-to-end systems — from hand-written retrieval cores and local-first inference pipelines to production APIs and clean, recruiter-proof frontends.

- **Software Engineering** — disciplined, test-driven development with an emphasis on correctness, observability, and maintainable architecture
- **AI / ML** — LLM application engineering, retrieval-augmented generation, agentic workflows, and CPU-constrained local inference
- **Full Stack** — typed backends, modern React frontends, and the DevOps glue that keeps them shipping
- **Product Mindset** — I build for users, not demos: measured performance, honest trade-offs, and iteration driven by real usage

**Open To:** Software Engineer · AI/ML Engineer · Full Stack Engineer roles — remote or hybrid, product-driven teams.

---

## Tech Stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=python,ts,js,cpp,bash,sqlite&theme=dark" alt="languages"/>

**Frontend**

<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,html,css,vite&theme=dark" alt="frontend"/>

**Backend & Databases**

<img src="https://skillicons.dev/icons?i=nodejs,fastapi,express,postgres,redis,mongodb&theme=dark" alt="backend"/>

**Cloud, DevOps & Tooling**

<img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,linux,nginx,git,github,githubactions&theme=dark" alt="devops"/>

</div>

---

## AI / ML Expertise

| Domain | Proficiency | Details |
|:-------|:-----------:|:--------|
| LLM Application Engineering | Advanced | Agentic coding assistants, tool-use orchestration, prompt architecture, evaluation loops |
| Retrieval-Augmented Generation | Advanced | Hand-written retrieval cores, chunking strategies, embedding pipelines (nomic-embed-text), hybrid ranking |
| Local & Edge Inference | Advanced | Ollama-based deployment, CPU-only serving, quantized models (GGUF), memory-constrained optimization |
| Agent Systems | Proficient | Multi-agent review pipelines, adversarial verification workflows, structured-output tooling |
| NLP | Proficient | Text normalization, low-resource language processing (Uzbek), classification and extraction pipelines |
| MLOps | Working | Model versioning, reproducible inference environments, latency/throughput benchmarking |

---

## Featured Projects

<details>
<summary><b>JOA — AI Coding Agent</b></summary>
<br/>

An autonomous AI coding agent that plans, edits, and verifies code changes through a local-first pipeline.

| | |
|:--|:--|
| **Stack** | Python, Ollama, local LLMs, CLI/REPL interface |
| **Scale** | Multi-file codebase operations with incremental context management |
| **Performance** | Runs fully on consumer CPU hardware — zero GPU dependency |
| **Security** | Local-first by design: no source code leaves the machine |
| **Impact** | Daily-driver coding assistant with tracked clone growth and public analytics |
| **Repository** | [TeamLider9141/JOA-AI-CODING-AGENT](https://github.com/TeamLider9141/JOA-AI-CODING-AGENT) |

Built to prove that a capable coding agent does not require cloud inference. The agent handles model selection, LaTeX-to-Unicode answer cleaning, uncertainty nudging, and ships with clone-statistics automation baked into CI.

</details>

<details>
<summary><b>System LLM — Local Retrieval-Core Coding Assistant</b></summary>
<br/>

A retrieval-augmented coding assistant with a **hand-written retrieval core** — no framework dependency — engineered for strict hardware budgets.

| | |
|:--|:--|
| **Stack** | Python, Ollama, qwen2.5-coder 7B, nomic-embed-text, custom vector store |
| **Scale** | Indexes real-world codebases in place — no corpus duplication |
| **Performance** | Tuned for CPU-only inference on 16 GB RAM (Ryzen 5800U class hardware) |
| **Security** | Fully offline operation; the index never touches a network |
| **Impact** | Replaces a LlamaIndex-based prototype with a leaner, fully understood core |
| **Repository** | Private — in active development |

The deliberate rewrite from framework-glue to first-principles retrieval: custom chunking, embedding, and ranking layers built to be read, measured, and tuned line by line.

</details>

<details>
<summary><b>Uzbek AI — Native-Language AI Tooling</b></summary>
<br/>

AI tooling and assistant workflows built for the Uzbek language — a low-resource NLP environment where off-the-shelf models underperform.

| | |
|:--|:--|
| **Stack** | Python, LLM prompt pipelines, custom skill/workflow definitions |
| **Scale** | Language-specific terminology handling across technical domains |
| **Performance** | Optimized prompt and context strategies for smaller local models |
| **Security** | Local execution; no user text sent to third-party services |
| **Impact** | Makes serious AI-assisted engineering workflows usable in Uzbek |
| **Repository** | [github.com/TeamLider9141](https://github.com/TeamLider9141) |

Bridges the gap between English-centric AI tooling and native-language engineering practice — from terminology mapping to full bilingual technical workflows.

</details>

---

## Experience

**AI Systems Engineer** · Independent / Open Source
<br/>*2024 — Present*

Design and delivery of local-first LLM systems: agentic coding assistants, hand-written RAG pipelines, and inference stacks that run on constrained consumer hardware.

- Architected a from-scratch retrieval core (chunking, embeddings, ranking) replacing a framework-based prototype
- Deployed and benchmarked quantized local models (GGUF via Ollama) for CPU-only production use
- Built multi-agent adversarial review workflows for answer verification and quality control
- Automated repository analytics, CI-driven documentation, and release hygiene across projects

`Python` `LLM Engineering` `RAG` `Ollama` `Agents` `CI/CD`

<br/>

**Systems & DevOps Engineering** · Contract / Assessment Work
<br/>*2023 — 2024*

Infrastructure and reliability engineering for large-scale multiplayer game server environments.

- Produced senior-level SRE runbooks: capacity math, SLO design, DR planning, and DDoS mitigation (conntrack-aware iptables strategies)
- Designed gateway drain strategies, async-queue backpressure policies, and RPO-correct backup schedules
- Authored incident-response playbooks covering database saturation, deployment failure, and observability outages

`Linux` `SRE` `Incident Response` `Capacity Planning` `Networking`

---

## Achievements

<div align="center">

| Recognition | Details |
|:-----------:|:--------|
| Local-First AI Pioneer | Shipped a fully offline AI coding agent — zero cloud dependency, tracked public adoption |
| Framework-Free RAG | Replaced LlamaIndex prototype with a hand-written retrieval core built for auditability |
| Senior SRE Assessment | Completed a senior MMO DevOps/SRE technical assessment through multi-round adversarial review |
| Consistent Contributor | Sustained daily open-source contribution streak with automated repo analytics |

</div>

---

## Certifications

**AWS**
<br/>
<img src="https://img.shields.io/badge/AWS_Certified_Cloud_Practitioner-232F3E?style=flat-square&logo=amazonwebservices&logoColor=FF9900" alt="aws-ccp"/>

**Oracle**
<br/>
<img src="https://img.shields.io/badge/OCI_Foundations_Associate-C74634?style=flat-square&logo=oracle&logoColor=white" alt="oci"/>

**NPTEL**
<br/>
<img src="https://img.shields.io/badge/Programming,_Data_Structures_%26_Algorithms-4F46E5?style=flat-square&logoColor=white" alt="nptel-dsa"/>
<img src="https://img.shields.io/badge/Machine_Learning-7C3AED?style=flat-square&logoColor=white" alt="nptel-ml"/>

**Cisco**
<br/>
<img src="https://img.shields.io/badge/CCNA:_Introduction_to_Networks-1BA0D7?style=flat-square&logo=cisco&logoColor=white" alt="ccna"/>
<img src="https://img.shields.io/badge/Cybersecurity_Essentials-049FD9?style=flat-square&logo=cisco&logoColor=white" alt="cyber"/>

---

## Coding Profiles

<div align="center">

<a href="https://leetcode.com/u/TeamLider9141"><img src="https://img.shields.io/badge/LeetCode-0D1117?style=for-the-badge&logo=leetcode&logoColor=FFA116" alt="leetcode"/></a>
<a href="https://www.geeksforgeeks.org/user/teamlider9141"><img src="https://img.shields.io/badge/GeeksforGeeks-0D1117?style=for-the-badge&logo=geeksforgeeks&logoColor=2F8D46" alt="gfg"/></a>
<a href="https://www.hackerrank.com/profile/johnuik006"><img src="https://img.shields.io/badge/HackerRank-0D1117?style=for-the-badge&logo=hackerrank&logoColor=00EA64" alt="hackerrank"/></a>
<a href="https://www.codechef.com/users/teamlider9141"><img src="https://img.shields.io/badge/CodeChef-0D1117?style=for-the-badge&logo=codechef&logoColor=white" alt="codechef"/></a>

</div>

---

## GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=TeamLider9141&show_icons=true&theme=midnight-purple&hide_border=true&bg_color=0D1117&count_private=true&include_all_commits=true" height="170" alt="stats"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=TeamLider9141&theme=midnight-purple&hide_border=true&background=0D1117" height="170" alt="streak"/>

<br/><br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=TeamLider9141&layout=compact&theme=midnight-purple&hide_border=true&bg_color=0D1117&langs_count=8" height="160" alt="top languages"/>

</div>

---

## GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=TeamLider9141&theme=discord&no-frame=true&no-bg=true&column=7&margin-w=8&margin-h=8" alt="trophies"/>

</div>

---

## Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=TeamLider9141&bg_color=0D1117&color=A78BFA&line=7C3AED&point=FFFFFF&area=true&area_color=4F46E5&hide_border=true" width="95%" alt="activity graph"/>

</div>

---

## Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/TeamLider9141/TeamLider9141/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/TeamLider9141/TeamLider9141/output/github-contribution-grid-snake.svg"/>
  <img src="https://raw.githubusercontent.com/TeamLider9141/TeamLider9141/output/github-contribution-grid-snake.svg" alt="contribution snake"/>
</picture>

</div>

---

## Current Focus

```yaml
learning:
  - Advanced retrieval architectures and embedding-space evaluation
  - Distributed systems patterns for real-time multiplayer backends
building:
  - System LLM — framework-free local RAG coding assistant
  - JOA — autonomous local AI coding agent
exploring:
  - Small-model agentic performance on CPU-only hardware
  - Low-resource NLP for the Uzbek language
open_to:
  - Software Engineer / AI Engineer / Full Stack roles
  - Open source collaboration on local-first AI tooling
```

---

## Connect

<div align="center">

<a href="mailto:johnuik006@gmail.com"><img src="https://img.shields.io/badge/Gmail-7C3AED?style=for-the-badge&logo=gmail&logoColor=white" alt="gmail"/></a>
<a href="https://www.linkedin.com/in/johnuik"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin"/></a>
<a href="https://github.com/TeamLider9141"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="github"/></a>
<a href="https://teamlider9141.github.io"><img src="https://img.shields.io/badge/Portfolio-4F46E5?style=for-the-badge&logo=vercel&logoColor=white" alt="portfolio"/></a>

</div>

---

<div align="center">

*Engineering is the discipline of making the right trade-offs — and owning every line that ships.*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:A78BFA,50:7C3AED,100:4F46E5&height=140&section=footer" width="100%" alt="footer"/>

</div>
