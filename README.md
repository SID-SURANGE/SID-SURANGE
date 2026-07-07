# Siddharth Surange · AI Engineer

<p>
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3000&pause=800&color=7AA2F7&background=1A1B27&center=true&vCenter=true&width=680&lines=Building+production-grade+AI+systems;Agentic+workflows+%2B+RAG+pipelines+%2B+local+LLM+tooling;Shipping+things+that+actually+run" alt="Typing SVG">
</p>

I build the layer between a raw LLM and something a business can actually rely on — retrieval that cites its sources instead of hallucinating them, and agents that fail loudly instead of silently.

🌐 **Portfolio:** [sid-surange.github.io](https://sid-surange.github.io) · 🔭 **Currently building:** [Briefcast](https://github.com/SID-SURANGE/briefcast) — an AI research briefing agent running in production for ~$8/month

---

## 👤 About Me

- 🧠 **What I do** — 10 years in software, last 2 focused on AI Engineering — shipping LLM-powered products to production, not just notebooks
- 🤖 **Right now** — deep in agentic dev tooling (Claude Code, Cursor), RAG that's actually evaluated (dedup, ranking, citations, before/after evals), and local quantized LLM setups
- 🏠 **How I build** — locally first (LM Studio, quantized Llama/Granite), cloud APIs only once it's proven
- ✍️ **Outside the day job** — writing on Medium about the parts of GenAI that are underdocumented, and shipping experiments to Hugging Face Spaces

---

<p align="center">
  <img src="https://github-readme-stats-rickstaa.vercel.app/api?username=SID-SURANGE&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&hide_rank=true" alt="GitHub Stats" height="165">
</p>

---

## ⚙️ Tech Stack

| Category | Tools |
|---|---|
| **Languages & AI** | ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white) ![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?logo=huggingface&logoColor=black) ![LangChain](https://img.shields.io/badge/LangChain-121D33?logo=chainlink&logoColor=white) ![OpenRouter](https://img.shields.io/badge/OpenRouter-6366F1?logoColor=white) |
| **Agentic Tooling** | ![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?logo=anthropic&logoColor=white) ![Cursor](https://img.shields.io/badge/Cursor-000000?logo=cursor&logoColor=white) ![LM Studio](https://img.shields.io/badge/LM%20Studio-4338CA?logoColor=white) |
| **Backend & Infra** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?logoColor=white) ![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?logo=google-cloud&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![Railway](https://img.shields.io/badge/Railway-0B0D0E?logo=railway&logoColor=white) |

---

## 🚀 Featured Projects

### [Briefcast](https://github.com/SID-SURANGE/briefcast)

Automated AI research briefing agent — monitors Google AI, DeepMind, OpenAI, Anthropic, arXiv and more, then delivers a curated daily digest to Telegram with follow-up Q&A over a 14-day rolling knowledge base.

**Stack:** FastAPI · PostgreSQL + pgvector · LangChain LCEL · OpenRouter (Gemini, Claude) · APScheduler · Railway
**Highlights:** dual-layer deduplication (SHA-256 + cosine similarity), tiered source ranking, RAG answers with citations, ~$8/month to run in production

### [claude-code-catalog](https://github.com/SID-SURANGE/claude-code-catalog)

Scans official and top community Claude Code repos for agents, skills, commands, and hooks, then lets you interactively install what you want straight into `~/.claude/` — with license tracking and attribution built in.

**Stack:** Python · Claude Code ecosystem tooling
**Highlights:** 8 curated sources (official + community) with per-repo license classification, unified scanning across heterogeneous repo layouts, interactive installer

### [cursor-team-ops](https://github.com/SID-SURANGE/cursor-team-ops)

A team-ops layer for Cursor — versioned rules, agent skills, and git guardrails that roll out across an entire engineering team in minutes, not sprints.

**Stack:** Shell · Cursor rules/skills · CI hooks
**Highlights:** 16 versioned skills (core + community tiers), 7 enforcement rule packs, 3 automated guardrail hooks (git-guard, migration-guard, license-gatekeeper), CODEOWNERS + CONTRIBUTING + SECURITY policy baked in

### [ResumeParser](https://github.com/SID-SURANGE/ResumeParser)

HR-focused resume analysis tool that runs entirely on local LLMs — no API keys required. Extracts structured data from PDFs, flags missing sections, generates tailored interview questions, and visualizes resume content.

**Stack:** FastAPI · Gradio · PyTorch · IBM Docling · LM Studio (quantized Llama 3.1/3.2, IBM Granite)
**Highlights:** fully offline, 8-bit quantized model support, spell-check analysis, word cloud generation

### [PageSense · AgentForge · AI-Sandbox](https://github.com/SID-SURANGE/AI-Sandbox)

Monorepo of production-grade experiments. **PageSense**: Chrome extension + FastAPI/Qdrant backend for semantic search over your browsing history. **AgentForge**: deployed agentic app with web search and image generation.

**Stack:** FastAPI · Qdrant · Gradio · smolagents · LlamaIndex · JavaScript (extension)

---

## 📝 Writing

- **[Briefcast: How I Built a Personal AI Intelligence Agent That Reads the Entire AI Ecosystem — For ~$10/Month](https://medium.com/@ssurange.dev/briefcast-how-i-built-a-personal-ai-intelligence-agent-that-reads-the-entire-ai-ecosystem-for-ac0f87d4fe65)**
- **[What's new with OpenAI's gpt-4o-mini](https://medium.com/@ssurange.dev/whats-new-with-openai-s-gpt-4o-mini-97a79e6047c3)**
- **[Deciphering the power of Vision Language Models](https://medium.com/@ssurange.dev/deciphering-the-power-of-vision-language-vision-language-models-b873e06daae5)**
- **[AgentForge: A simple AI Agent with Web Search and Image Generation](https://medium.com/@ssurange.dev/agentforge-a-simple-ai-agent-with-web-search-and-image-generation-capabilities-8c756f047c05)**
- **[ProGAN, StyleGAN, StyleGAN2: Exploring NVIDIA's breakthroughs](https://medium.com/@sidsurange/c90ddb7f9b61#264d-2312224d64e4)**

---

## 🎓 Certifications

Oracle Certified Generative AI Professional · Google Cloud Professional Data Engineer

---

## 🔗 Connect

<p align="center">
  <a href="https://sid-surange.github.io" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-22C55E.svg?style=for-the-badge&logo=astro&logoColor=white" alt="Portfolio">
  </a>
  <a href="https://www.linkedin.com/in/siddharthsurange/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://huggingface.co/SIDS92" target="_blank">
    <img src="https://img.shields.io/badge/HuggingFace-%23FF6F00.svg?style=for-the-badge&logo=huggingface&logoColor=white" alt="Hugging Face">
  </a>
  <a href="https://medium.com/@ssurange.dev" target="_blank">
    <img src="https://img.shields.io/badge/Medium-%23000000.svg?style=for-the-badge&logo=medium&logoColor=white" alt="Medium">
  </a>
  <a href="mailto:ssurange.dev@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335.svg?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>
