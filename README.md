# Siddharth Surange · AI Engineer

<p>
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3000&pause=800&color=7AA2F7&background=1A1B27&center=true&vCenter=true&width=680&lines=Building+production-grade+AI+systems;Agentic+workflows+%2B+RAG+pipelines+%2B+local+LLM+tooling;Shipping+things+that+actually+run" alt="Typing SVG">
</p>

I build the layer between a raw LLM and something a business can actually rely on — retrieval that cites its sources instead of hallucinating them, and agents that fail loudly instead of silently.

---

## 👤 About Me

- 🧠 **What I do** — 10 years in software, last 2 focused on AI Engineering — shipping LLM-powered products to production, not just notebooks
- 🤖 **Right now** — deep in agentic dev tooling (Claude Code, Cursor), RAG that's actually evaluated (dedup, ranking, citations, before/after evals), and local quantized LLM setups
- 🏠 **How I build** — locally first (LM Studio, quantized Llama/Granite), cloud APIs only once it's proven
- ✍️ **Outside the day job** — writing on Medium about the parts of GenAI that are underdocumented, and shipping experiments to Hugging Face Spaces

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=SID-SURANGE&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" height="165">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=SID-SURANGE&theme=tokyonight&hide_border=true" alt="GitHub Streak" height="165">
</p>

---

## ⚙️ Tech Stack

| Category | Tools |
|---|---|
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) |
| **Agentic Dev Tooling** | ![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white) ![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white) ![Cursor](https://img.shields.io/badge/Cursor-000000?style=for-the-badge&logo=cursor&logoColor=white) |
| **LLM Orchestration** | ![LangChain](https://img.shields.io/badge/LangChain-121D33?style=for-the-badge&logo=chainlink&logoColor=white) ![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=for-the-badge&logoColor=white) ![OpenRouter](https://img.shields.io/badge/OpenRouter-6366F1?style=for-the-badge&logoColor=white) |
| **Models & Embeddings** | ![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white) |
| **Backend & Data** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logoColor=white) |
| **Cloud & Infra** | ![Google Cloud Platform](https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white) ![Vertex AI](https://img.shields.io/badge/Vertex%20AI-34A853?style=for-the-badge&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white) |
| **UI** | ![Gradio](https://img.shields.io/badge/Gradio-FF7043?style=for-the-badge&logoColor=white) |

---

## 🚀 Featured Projects

<table>
  <tr>
    <td width="25%" align="center" style="padding: 20px;">
      <a href="https://github.com/SID-SURANGE/briefcast">
        <img width="100%" src="https://github-readme-stats.vercel.app/api/pin/?username=SID-SURANGE&repo=briefcast&theme=tokyonight" alt="Briefcast">
      </a>
    </td>
    <td width="75%" style="padding: 20px;">
      <h3>Briefcast</h3>
      <p>Automated AI research briefing agent — monitors Google AI, DeepMind, OpenAI, Anthropic, arXiv and more, then delivers a curated daily digest to Telegram with follow-up Q&A over a 14-day rolling knowledge base.</p>
      <p><strong>Stack:</strong> FastAPI · PostgreSQL + pgvector · LangChain LCEL · OpenRouter (Gemini, Claude) · APScheduler · Railway</p>
      <p><strong>Highlights:</strong> dual-layer deduplication (SHA-256 + cosine similarity), tiered source ranking, RAG answers with citations, ~$8/month to run in production</p>
    </td>
  </tr>
  <tr>
    <td width="25%" align="center" style="padding: 20px;">
      <a href="https://github.com/SID-SURANGE/claude-code-catalog">
        <img width="100%" src="https://github-readme-stats.vercel.app/api/pin/?username=SID-SURANGE&repo=claude-code-catalog&theme=tokyonight" alt="Claude Code Catalog">
      </a>
    </td>
    <td width="75%" style="padding: 20px;">
      <h3>claude-code-catalog</h3>
      <p>Scans official and top community Claude Code repos for agents, skills, commands, and hooks, then lets you interactively install what you want straight into <code>~/.claude/</code> — with license tracking and attribution built in.</p>
      <p><strong>Stack:</strong> Python · Claude Code ecosystem tooling</p>
      <p><strong>Highlights:</strong> 8 curated sources (official + community) with per-repo license classification, unified scanning across heterogeneous repo layouts, interactive installer</p>
    </td>
  </tr>
  <tr>
    <td width="25%" align="center" style="padding: 20px;">
      <a href="https://github.com/SID-SURANGE/cursor-team-ops">
        <img width="100%" src="https://github-readme-stats.vercel.app/api/pin/?username=SID-SURANGE&repo=cursor-team-ops&theme=tokyonight" alt="Cursor Team Ops">
      </a>
    </td>
    <td width="75%" style="padding: 20px;">
      <h3>cursor-team-ops</h3>
      <p>A team-ops layer for Cursor — versioned rules, agent skills, and git guardrails that roll out across an entire engineering team in minutes, not sprints.</p>
      <p><strong>Stack:</strong> Shell · Cursor rules/skills · CI hooks</p>
      <p><strong>Highlights:</strong> 16 versioned skills (core + community tiers), 7 enforcement rule packs, 3 automated guardrail hooks (git-guard, migration-guard, license-gatekeeper), CODEOWNERS + CONTRIBUTING + SECURITY policy baked in</p>
    </td>
  </tr>
  <tr>
    <td width="25%" align="center" style="padding: 20px;">
      <a href="https://github.com/SID-SURANGE/ResumeParser">
        <img width="100%" src="https://github-readme-stats.vercel.app/api/pin/?username=SID-SURANGE&repo=ResumeParser&theme=tokyonight" alt="Resume Parser">
      </a>
    </td>
    <td width="75%" style="padding: 20px;">
      <h3>ResumeParser</h3>
      <p>HR-focused resume analysis tool that runs entirely on local LLMs — no API keys required. Extracts structured data from PDFs, flags missing sections, generates tailored interview questions, and visualizes resume content.</p>
      <p><strong>Stack:</strong> FastAPI · Gradio · PyTorch · IBM Docling · LM Studio (quantized Llama 3.1/3.2, IBM Granite)</p>
      <p><strong>Highlights:</strong> fully offline, 8-bit quantized model support, spell-check analysis, word cloud generation</p>
    </td>
  </tr>
  <tr>
    <td width="25%" align="center" style="padding: 20px;">
      <a href="https://github.com/SID-SURANGE/AI-Sandbox">
        <img width="100%" src="https://github-readme-stats.vercel.app/api/pin/?username=SID-SURANGE&repo=AI-Sandbox&theme=tokyonight" alt="AI Sandbox">
      </a>
    </td>
    <td width="75%" style="padding: 20px;">
      <h3>PageSense · AgentForge · AI-Sandbox</h3>
      <p>Monorepo of production-grade experiments. <strong>PageSense</strong>: Chrome extension + FastAPI/Qdrant backend for semantic search over your browsing history. <strong>AgentForge</strong>: deployed agentic app with web search and image generation.</p>
      <p><strong>Stack:</strong> FastAPI · Qdrant · Gradio · smolagents · LlamaIndex · JavaScript (extension)</p>
    </td>
  </tr>
</table>

---

## 📝 Writing

- **[Briefcast: How I Built a Personal AI Intelligence Agent That Reads the Entire AI Ecosystem — For ~$10/Month](https://medium.com/@ssurange.dev/briefcast-how-i-built-a-personal-ai-intelligence-agent-that-reads-the-entire-ai-ecosystem-for-ac0f87d4fe65)**
- **[What's new with OpenAI's gpt-4o-mini](https://medium.com/@ssurange.dev/whats-new-with-openai-s-gpt-4o-mini-97a79e6047c3)**
- **[Deciphering the power of Vision Language Models](https://medium.com/@ssurange.dev/deciphering-the-power-of-vision-language-vision-language-models-b873e06daae5)**
- **[AgentForge: A simple AI Agent with Web Search and Image Generation](https://medium.com/@ssurange.dev/agentforge-a-simple-ai-agent-with-web-search-and-image-generation-capabilities-8c756f047c05)**
- **[ProGAN, StyleGAN, StyleGAN2: Exploring NVIDIA's breakthroughs](https://medium.com/@sidsurange/c90ddb7f9b61#264d-2312224d64e4)**

---

## 🎓 Certifications

- Oracle Certified Generative AI Professional
- Google Cloud Professional Data Engineer

---

## 🔗 Connect

<p align="center">
  <a href="https://www.linkedin.com/in/siddharthsurange/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://huggingface.co/SIDS92" target="_blank">
    <img src="https://img.shields.io/badge/HuggingFace-%23FF6F00.svg?style=for-the-badge&logo=huggingface&logoColor=white" alt="Hugging Face">
  </a>
  <a href="https://medium.com/@ssurange.dev" target="_blank">
    <img src="https://img.shields.io/badge/Medium-%23000000.svg?style=for-the-badge&logo=medium&logoColor=white" alt="Medium">
  </a>
</p>
