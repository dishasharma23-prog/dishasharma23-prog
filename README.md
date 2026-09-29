## Hi there 👋

<div align="center">

# Hey, I'm Disha 👋

**Student developer · AI & Security · Full-stack builder**

*I build things that are trustworthy, secure, and useful to real people.*

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=8B5CF6&center=true&vCenter=true&width=640&lines=Verifying+impact+evidence+with+AI+%F0%9F%93%B8;Auditing+codebases+with+RAG+%F0%9F%9B%A1%EF%B8%8F;Securing+SDN+routing+with+fuzzy+logic+%F0%9F%8C%90;Giving+AI+agents+bounded+wallets+%F0%9F%92%B8" alt="Typing animation" />

</div>

---

## 🌱 About me

- 🎓 Student at **NIIT University, Neemrana**
- 🔐 I care about **trust and security**: in networks, in code, and in the evidence behind claims
- 🤖 Building **AI-powered full-stack products** with Next.js, FastAPI and RAG pipelines
- 🐳 Comfortable shipping with **Docker, Jenkins and cloud deploys**
- 🦈 Earned the **Pull Shark** achievement on GitHub

---

## 🚀 Featured projects

### 📸 [ImpactProof](https://github.com/dishasharma23-prog/impactproof) · [Live](https://impactproof-web.onrender.com/)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Postgres](https://img.shields.io/badge/Postgres-4169E1?style=flat&logo=postgresql&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=flat&logo=cloudinary&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white)

> **Evidence you can trace. Impact you can trust.** Donors increasingly doubt impact photos, so ImpactProof turns NGO field photos into verified evidence and verified evidence into claims anyone can check.

- **Nine explainable checks** (GPS, capture date, photo reuse, C2PA credentials, camera metadata, visual content, visible text, weather and more) produce a verdict: *Corroborated, Needs review, Suspicious* or *Unverifiable*
- **AI observes, rules decide, people resolve**: uncertain cases go to a review queue with an append-only audit log
- Claims get an **impact brief with a QR code** that opens a public verification page (faces blurred, locations rounded)
- Photos are sorted automatically by stage, activity, site and day, and tagged with the UN SDGs they support
- Includes an offline-first field app with on-device semantic memory (Qdrant Edge)

*Built for Code Cubicle 6.0 (Problem Statement 02, Cloudinary).*

---

### 🛡️ [CodeSentry](https://github.com/dishasharma23-prog/CodeSentry)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

> An **AST-aware RAG security auditor** for understanding and analysing unfamiliar codebases. Point it at a public GitHub repo, ask questions, and it surfaces security vulnerabilities.

- Microservice architecture: Next.js frontend, Node/Express backend, Python/FastAPI RAG service
- **Hybrid retrieval** (ChromaDB embeddings + BM25L keyword search) with cross-encoder reranking
- Citation highlighting and an interactive source viewer, with repository-scoped isolation so context never leaks between repos
- One-command deployment with Docker Compose

---

### 💸 [AgentPay](https://github.com/dishasharma23-prog/AgentPay) · [Live demo](https://agent-pay-eta.vercel.app)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Web3](https://img.shields.io/badge/Web3-concept-F16822?style=flat)

> **The financial layer for autonomous agents.** A product concept exploring *bounded financial autonomy*: give AI agents the ability to pay for services without giving them unrestricted control of a wallet.

- Interactive simulation of agent permissions, budgets, escrow, transactions and settlement
- The user always owns the funds, and agents operate inside explicit limits
- *Demo only: no real funds are moved.*

---

### 🌐 [SDN-AI-routing-optimization](https://github.com/dishasharma23-prog/SDN-AI-routing-optimization)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Mininet](https://img.shields.io/badge/Mininet-SDN-blue?style=flat)
![Ryu](https://img.shields.io/badge/Ryu-OpenFlow-orange?style=flat)

> **Security runs first.** Most fuzzy routing approaches pick the fastest node and then check if it's safe. This flips the order: a compromised node scores zero and can never be selected.

- 6-step security pipeline (subnet, blacklist, certificates, pinning, CRL, HMAC-SHA256) feeding a **trust multiplier** into the fuzzy routing score
- Tested on the Sprint ISP topology under heavy load with compromised nodes

| Metric | OSPF | RIP | **This project** |
|---|---|---|---|
| Packet loss | 13.22% | 15.10% | **0.53%** |
| Latency | 278.7 ms | 297.0 ms | **18.2 ms** |
| Compromised nodes blocked | 0/11 | 0/11 | **2/11** |

*R&D project at NIIT University with teammates, supervised by Dr. Shweta Malwe.*

---

### 💜 [SoulCare Bot](https://github.com/dishasharma23-prog/soulcare-bot) · [Live demo](https://soulcare-bot.vercel.app/chatbot)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)

> An AI companion for emotional support, built for students who are far from home and just need someone to talk to.

- Empathetic chat for daily check-ins
- Weekly reports that summarise emotional patterns, plus an insights dashboard for self-reflection

---

### 🔌 [Corsair](https://github.com/corsairdev/corsair) ![Stars](https://img.shields.io/github/stars/corsairdev/corsair?style=flat&logo=github)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)

> Open-source toolkit for connecting your users to their apps, one of the projects I'm involved with in the open-source community.

---

## 🧰 Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

**Also working with:** RAG · ChromaDB · Gemini · Mininet · Ryu · OpenFlow · Cloudinary · Vercel · Render

---

## 📊 GitHub stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=dishasharma23-prog&show_icons=true&theme=radical&hide_border=true" alt="GitHub stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=dishasharma23-prog&layout=compact&theme=radical&hide_border=true" alt="Top languages" />

</div>

---

<div align="center">

**Thanks for stopping by. If something here interests you, say hi or drop a ⭐**

![Profile views](https://komarev.com/ghpvc/?username=dishasharma23-prog&color=8B5CF6&style=flat-square&label=PROFILE+VIEWS)

</div>
