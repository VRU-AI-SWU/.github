# VRU-AI SWU

> **Department of Computer Science, Faculty of Science**  
> Srinakharinwirot University (SWU), Bangkok, Thailand

**VRU-AI SWU** is a Virtual Research Unit within the Computer Science department at Srinakharinwirot University. We apply artificial intelligence, machine learning, and modern software engineering to drive transformation across four pillars — helping our department, our students, and our stakeholders move further and faster through intelligent systems.

---

## Our Mission

To modernize the CS department at SWU by building practical AI-powered systems that elevate the quality of teaching, streamline operations, deepen research capability, and improve services for students, faculty, and the wider community.

---

## Four Pillars of Excellence

| Pillar | Goal |
|--------|------|
| <div align="center"><img src="https://raw.githubusercontent.com/SWU-CS-Intelligence-Lab/.github/main/logos/learning-excellence.png" width="40"/><br/>**Learning Excellence**</div> | Equip students with hands-on AI/ML tools and up-to-date curricula that reflect real-world skill demands |
| <div align="center"><img src="https://raw.githubusercontent.com/SWU-CS-Intelligence-Lab/.github/main/logos/operation-excellence.png" width="40"/><br/>**Operation Excellence**</div> | Automate and optimize departmental processes through data-driven and AI-assisted workflows |
| <div align="center"><img src="https://raw.githubusercontent.com/SWU-CS-Intelligence-Lab/.github/main/logos/researech-excellence.png" width="40"/><br/>**Research Excellence**</div> | Build and share open platforms that accelerate empirical research, particularly in machine learning and few-shot learning |
| <div align="center"><img src="https://raw.githubusercontent.com/SWU-CS-Intelligence-Lab/.github/main/logos/service%20excellence.png" width="40"/><br/>**Service Excellence**</div> | Deliver intelligent front-facing services — chatbots, analytics tools — that better serve students, faculty, and industry partners |

---

## Projects

<table>
  <tr>
    <td width="180" align="center" valign="top">
      <img src="https://raw.githubusercontent.com/SWU-CS-Intelligence-Lab/.github/main/logos/chiron.svg" width="120"/><br/><br/>
      <strong>Chiron</strong><br/>
      <em>AI Learning Sandbox</em>
    </td>
    <td valign="top">
      <strong>Pillar:</strong> Learning Excellence<br/><br/>
      A containerized educational platform for AI and Reinforcement Learning courses. Instructors publish AI challenges; students upload trained agents (Python scripts or model weights) which are evaluated inside isolated Docker containers against hidden Gymnasium environments. Global leaderboards rank teams in real time.<br/><br/>
      <ul>
        <li><strong>Key Features:</strong> Google OAuth SSO, team management, agent submission pipeline, isolated evaluation engine, real-time leaderboards</li>
        <li><strong>Activities Planned:</strong> Multi-Armed Bandit → DQN → Policy Gradients → Agentic Workflows</li>
        <li><strong>Stack:</strong> Next.js · FastAPI · PostgreSQL · Redis/Celery · Docker · Gymnasium (OpenAI Gym)</li>
      </ul>
    </td>
  </tr>
  <tr><td colspan="2"><br/></td></tr>
  <tr>
    <td width="180" align="center" valign="top">
      <img src="https://raw.githubusercontent.com/SWU-CS-Intelligence-Lab/.github/main/logos/heimdall.svg" width="120"/><br/><br/>
      <strong>Heimdall</strong><br/>
      <em>Few-Shot Learning Platform</em>
    </td>
    <td valign="top">
      <strong>Pillar:</strong> Research Excellence<br/><br/>
      A full-stack web platform for building, training, and evaluating few-shot learning (FSL) models. Built for research teams who work with small labeled image datasets, Heimdall provides the full workflow from dataset management and support set selection, to episodic training, statistical evaluation, and model management — all through a browser.<br/><br/>
      <ul>
        <li><strong>Key Features:</strong> Multi-workspace isolation, role-based access (Owner / Editor / Viewer), image dataset management, episodic training with DinoV2 backbone, confidence-interval reports, ROC curves, scatter plots, saved model management</li>
        <li><strong>Stack:</strong> Next.js 14 · FastAPI · PostgreSQL · PyTorch · DinoV2 · Celery · Redis · Docker</li>
      </ul>
    </td>
  </tr>
  <tr><td colspan="2"><br/></td></tr>
  <tr>
    <td width="180" align="center" valign="top">
      <img src="https://raw.githubusercontent.com/SWU-CS-Intelligence-Lab/.github/main/logos/iris.svg" width="120"/><br/><br/>
      <a href="https://github.com/VRU-AI-SWU/iris"><strong>IRIS</strong></a><br/>
      <em>Skill Gap Intelligence System</em>
    </td>
    <td valign="top">
      <strong>Pillar:</strong> Research Excellence · Learning Excellence<br/><br/>
      An agentic AI system that quantifies the gap between what an academic programme teaches and what the current job market demands. IRIS ingests curriculum documents, scrapes job postings across career paths and business sectors, and applies NLP and statistical models (cosine similarity, KL divergence, chi-square) to surface under-supplied and over-supplied skills — enabling data-driven curriculum decisions.<br/><br/>
      <ul>
        <li><strong>Key Features:</strong> Multi-format curriculum ingestion (PDF, DOCX, HTML, YAML/JSON), job market harvesting agent, standardized skill taxonomy, gap scoring engine, prioritized curriculum recommendations, trend analysis</li>
        <li><strong>Stack:</strong> Next.js · FastAPI · LangGraph/LangChain · LM Studio (gemma-4-31b-it) · spaCy · scikit-learn · Scrapy · Docker</li>
      </ul>
    </td>
  </tr>
  <tr><td colspan="2"><br/></td></tr>
  <tr>
    <td width="180" align="center" valign="top">
      <img src="https://raw.githubusercontent.com/SWU-CS-Intelligence-Lab/.github/main/logos/janus.svg" width="120"/><br/><br/>
      <strong>Janus</strong><br/>
      <em>Agentic Admission Chatbot</em>
    </td>
    <td valign="top">
      <strong>Pillar:</strong> Service Excellence<br/><br/>
      An agentic RAG chatbot embedded in the CS department's website (<code>cs.science.swu.ac.th</code>) to answer prospective students' questions about admissions (TCAS criteria, application rounds, curriculum, career paths). Built with a <strong>multi-agent architecture</strong> (Router · Admission · Academic agents), it also serves as a live teaching project for CS TAs to learn AI architecture, tool calling, and containerized deployment.<br/><br/>
      <ul>
        <li><strong>Key Features:</strong> Embedded WordPress widget, multi-agent orchestration (LangGraph), RAG over department knowledge base, session memory, on-premise GPU deployment</li>
        <li><strong>Stack:</strong> HTML/JS widget · FastAPI · LangGraph · LM Studio (qwen3.6-27b) · ChromaDB · BGE-m3 embeddings · Redis · Docker</li>
      </ul>
    </td>
  </tr>
</table>

---

## Student Showcases

Projects in this section are independent studies by lab advisees. They are built under lab supervision and reflect the same technical standards as core lab projects.

<table>
  <tr>
    <td width="180" align="center" valign="top">
      <img src="https://raw.githubusercontent.com/SWU-CS-Intelligence-Lab/.github/main/logos/homa.svg" width="120"/><br/><br/>
      <strong>HOMA</strong><br/>
      <em>Hotel Market Analytics</em>
    </td>
    <td valign="top">
      <strong>Type:</strong> Independent Study &nbsp;·&nbsp; <strong>Pillar:</strong> Service Excellence · Operation Excellence<br/><br/>
      An AI-powered market intelligence tool for hotel revenue teams. HOMA ingests raw room listings from OTA websites, uses a local LLM (gemma-4-31b-it via LM Studio) to standardize messy room descriptions against a user-defined schema, then applies K-Means clustering and PCA to map competitive market positioning — all visualized on an interactive market map with AI-generated cluster insights.<br/><br/>
      <ul>
        <li><strong>Key Features:</strong> User-defined feature schema, LLM standardization (fully local, no cloud API), K-Means clustering, PCA market map, AI-generated cluster summaries, real-time SSE progress streaming</li>
        <li><strong>Stack:</strong> Next.js · FastAPI · LM Studio (gemma-4-31b-it) · scikit-learn · Recharts · Docker</li>
        <li><strong>Location:</strong> <code>student-showcases/homa/</code></li>
      </ul>
    </td>
  </tr>
</table>

---

## Teaching Materials

The `swu-courses/` repository contains lecture notes and tutorials authored for CS SWU students:

| Course | Contents |
|--------|----------|
| [**Artificial Intelligence**](https://github.com/VRU-AI-SWU/swu-courses/tree/main/artificial-intelligence) | 15-week course — Part 1: RL fundamentals (MDP, Bellman, Q-Learning, DQN, PPO); Part 2: LLMs & Agentic AI (Transformers, LoRA, RLHF, ReAct, RAG, Multi-Agent, Safety) |
| **Git & GitHub Tutorials** | 5-part hands-on series for students with no prior experience (Concepts → Setup → Solo Workflow → Common Situations → Collaboration) |
| **Data Analytics** | *(Coming soon)* |
| **Statistics** | *(Coming soon)* |

---

## Technology Themes

All lab projects share a common philosophy and technology foundation:

- **Local-first AI** — LLMs run on-premise via [LM Studio](https://lmstudio.ai/), keeping data private and eliminating cloud API costs
- **Containerized everything** — Docker Compose for reproducible, one-command deployment
- **Modern full-stack** — Next.js (App Router) frontends, FastAPI backends, async PostgreSQL, Redis queues
- **Agent-native design** — LangGraph/LangChain in every system that requires reasoning, planning, or multi-step tool use
- **Research-grade rigor** — Statistical evaluation (confidence intervals, hypothesis testing) built into platforms, not bolted on

---

## Getting Started

Each project lives in its own directory (and will have its own repository). Refer to the individual project's `readme.md` for setup instructions.

```bash
# General pattern — start any project with Docker Compose
cd <project-folder>
docker compose up --build
```

Most projects require:
- Docker Engine ≥ 24 with Compose v2
- LM Studio running locally with the required model loaded (for LLM-dependent services)
- A `.env` file configured from the provided `.env.example`

---

## Contact

| | |
|-|-|
| **Lab** | VRU-AI SWU |
| **Department** | Computer Science, Faculty of Science, Srinakharinwirot University |
| **GitHub Organization** | [github.com/VRU-AI-SWU](https://github.com/VRU-AI-SWU) |

---

*Building intelligent systems that serve learning, operations, research, and people.*
