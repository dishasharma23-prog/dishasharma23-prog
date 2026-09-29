# Disha Sharma

<sub>**CSE (AI/ML) @ NIIT University** · AI · Security · Full-stack</sub>

---

## 👩‍💻 About Me

- 🎓 Computer Science & Engineering (**AI/ML**) student at **NIIT University, Neemrana**
- 📸 Built **ImpactProof**, which turns NGO field photos into verified, donor-checkable evidence
- 🛡️ Built **CodeSentry**, an AST-aware RAG security auditor for unfamiliar codebases
- 🌐 Researched **secure SDN routing** with fuzzy logic (R&D project, supervised by Dr. Shweta Malwe)
- 🧱 Building full-stack products with **Next.js, TypeScript, FastAPI and Node.js**
- 🐳 Shipping with **Docker, Docker Compose and Jenkins**
- 💜 Made **SoulCare**, an emotional support chatbot for students living away from home
- 🦈 Merging pull requests on GitHub (Pull Shark achievement)

---

## 🚀 Featured Projects

### 📸 [ImpactProof](https://github.com/dishasharma23-prog/impactproof) · [Live](https://impactproof-web.onrender.com/)
`Python` `FastAPI` `Next.js` `PostgreSQL` `Cloudinary` `Gemini`

[![ImpactProof landing page](assets/impactproof.png)](https://impactproof-web.onrender.com/)

**Problem:** Donors doubt impact photos: recycled images, wrong locations, stock and AI-generated pictures.
**Solution:** Nine explainable checks (GPS, capture date, reuse, C2PA credentials, metadata, visual content, visible text, weather and more) give every photo a verdict: *Corroborated, Needs review, Suspicious* or *Unverifiable*. Uncertain cases go to a human review queue with an append-only audit log, and each claim gets a QR-coded public verification page.
**Built for:** Code Cubicle 6.0 (Cloudinary problem statement).

### 🛡️ [CodeSentry](https://github.com/dishasharma23-prog/CodeSentry)
`Next.js` `Node.js` `FastAPI` `MongoDB` `ChromaDB` `Docker`

**Problem:** Understanding and auditing an unfamiliar codebase is slow.
**Solution:** Point it at a public GitHub repo and ask questions. Hybrid retrieval (embeddings + BM25L) with cross-encoder reranking surfaces answers and security findings with highlighted citations, and each repo is isolated so context never leaks between codebases.

### 🌐 [SDN-AI-routing-optimization](https://github.com/dishasharma23-prog/SDN-AI-routing-optimization)
`Python` `Mininet` `Ryu` `OpenFlow`

**Problem:** OSPF and RIP will happily route through a fast node that has been compromised.
**Solution:** A 6-step security pipeline feeds a trust multiplier into a fuzzy routing score, so a compromised node scores zero and is never selected.

| Metric (Sprint ISP topology, heavy load) | OSPF | RIP | This project |
|---|---|---|---|
| Packet loss | 13.22% | 15.10% | **0.53%** |
| Latency | 278.7 ms | 297.0 ms | **18.2 ms** |
| Compromised nodes blocked | 0/11 | 0/11 | **2/11** |

### 💸 [AgentPay](https://github.com/dishasharma23-prog/AgentPay)
`TypeScript` `Next.js` `Tailwind`

**Problem:** AI agents need to pay for things, but unrestricted wallet access is dangerous.
**Solution:** A product concept for *bounded financial autonomy*: agents work within user-defined budgets, permissions and escrow. Simulation only, no real funds move.

### 💜 [SoulCare Bot](https://github.com/dishasharma23-prog/soulcare-bot) · [Live](https://soulcare-bot.vercel.app/chatbot)
`Next.js` `TypeScript` `Vercel`

**Problem:** Students far from home sometimes just need someone to talk to.
**Solution:** An empathetic chatbot for daily check-ins, with weekly reports and an insights dashboard that help users reflect on their mood over time.

### 🔌 [Corsair](https://github.com/corsairdev/corsair)
`TypeScript`

Open-source toolkit for connecting your users to their apps.

---

## 🧰 Tech Stack

**Languages:** Python · TypeScript · JavaScript
**Frontend:** React · Next.js · Tailwind CSS
**Backend:** Node.js · Express · FastAPI
**Data & AI:** MongoDB · PostgreSQL · ChromaDB · RAG · Gemini
**DevOps:** Docker · Jenkins · Linux · Git · Vercel · Render
**Networking:** Mininet · Ryu · OpenFlow

---

<sub>Thanks for stopping by. If something here interests you, drop a ⭐</sub>
