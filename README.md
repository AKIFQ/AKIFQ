<!-- Typing SVG banner -->
<p align="center">
  <img
    src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&pause=1000&color=58A6FF&center=true&vCenter=true&width=800&lines=Hi%2C+I'm+Akif+Azher+Qureshi.;Engineer+%E2%86%92+AI+Architect.;Creator+of+Zed+%E2%80%94+Shadow+VCS+for+Agents."
    alt="typing intro"
  />
</p>

<!-- Shields badges -->
<p align="center">
  <img src="https://img.shields.io/badge/React-%2361DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Python-%233776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-%23ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-%2347A248?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/LLM%20Prompts-%23FFB000?style=for-the-badge" />
  <img src="https://img.shields.io/badge/MCP-Enabled-%2300C7B7?style=for-the-badge" />
</p>

---

### Core Toolkit
| Layer | Tech |
| :---  | :--- |
| **Interfaces** | React · Tailwind CSS |
| **Logic** | Java · Python |
| **Data** | MongoDB · PostgreSQL · Redis |
| **AI / Agents** | OpenAI API · LangChain · MCP protocol |
| **DevOps** | Git · GitHub Actions · Vite |

---

### Projects

#### **ZED – Shadow VCS for AI Agents**
<details>
<summary>Local-first staging VCS that quarantines, fingerprints & risk-scores AI-generated code before it reaches Git.</summary>

# ZED (Shadow VCS) – A Staging Version Control System for AI Agents

## What is ZED?
**ZED** is a local-first staging VCS that sits between AI agents (or any code generator) and your production Git repo, acting as a “spam filter for code.”

## Why it matters
1. Catches vulnerabilities, hard-coded secrets, unsafe patterns  
2. Creates a tamper-proof audit trail for compliance  
3. Gives humans the final word on agent commits  
4. Automates risk scoring & policy gates  
5. Keeps all code private and offline

## How it works
```
AI Agent → ZED (Staging) → Human Review → Production Git
```
* Commit quarantine in `.zed/commits/*`  
* SQLite audit DB + SHA-256 fingerprints  
* YAML policy engine (auto-approve, flag, block)  
* Risk factors: file sensitivity, secret scans, binary size, deletion patterns

## CLI quick-start
```bash
pip install zedai
zed init
echo 'print("hello")' > hello.py
zed commit -m "AI: add hello"
zed review <id> && zed approve <id>
```

Future roadmap: LangChain hooks, multi-agent audit trails, CI/CD glue, team roles.

</details>

#### [**Ordelo** · Recipe & Grocery Platform](https://ordelo.org/)
Full-stack MERN service connecting local vendors to shoppers.  
- Led end-to-end build with **MongoDB, React, Node, Express**  
- Context API + custom hooks reduced code complexity by **40 %**  
- Intelligent caching layer cut external API traffic **60 %** and enabled offline mode  
- Nested MongoDB schema supports multi-vendor ordering at scale  

#### **Ether Wallet** · Ethereum Transaction UI  
Lightweight React front-end for sending, signing, and monitoring ETH transfers.  
- **Vite-powered** build trims load times ~40 %  
- **Ethers.js** handles wallet connections; 100 + test-net txs validated  
- Solidity contracts > 90 % coverage via **Hardhat** CI; avg confirmation ↓ to ~10 s  

#### [**Personal Portfolio** · akifq.com](https://akifq.com/)
Mobile-first site showcasing work & writing.  
- Vanilla **HTML5/CSS3/JS** with modular, BEM-style CSS  
- Semantic markup, WCAG-AA contrast, responsive breakpoints at 700 px & 1000 px  
- Service-worker cache for instant repeat visits  

---

### Current Focus
<details>
  <summary>Agentic AI & Prompt Engineering</summary>

  * Extending **Zed** to support multi-agent cooperation and audit trails.  
  * Experimenting with **Model Context Protocol (MCP)** to share agent memory safely.  
  * Researching retrieval-augmented generation (RAG) for long-context coding agents.
</details>

---

### 👋 Reach Me
- 📍 New York City  
- ✉️ akifazherq@gmail.com  
- 🌐 [LinkedIn](https://www.linkedin.com/in/akifqureshi/)

<p align="center">
  <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https://github.com/AKIFQ&title=Profile+Visits" alt="visit counter"/>
</p>
