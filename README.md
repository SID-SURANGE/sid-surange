# Siddharth Surange · AI Engineer

Building production-grade AI systems — from RAG pipelines and agentic workflows to local LLM tooling. I work at the intersection of **Generative AI**, **NLP**, and **MLOps**, with a focus on shipping things that actually run.

---

## About Me

- **Day job**: AI Engineer, building LLM-powered products in production
- **Current interests**: Agentic architectures, RAG with real retrieval quality (deduplication, ranking, citations), and local LLM setups with quantized models
- **How I work**: I prefer running things locally first — LM Studio, quantized Llama/Granite models — before scaling to cloud APIs
- **Community**: I write on Medium about things I wish were better documented, and I deploy experiments to Hugging Face Spaces

---

## 🛠️ Tech Stack

| Category | Tools |
|---|---|
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) |
| **LLM Orchestration** | ![LangChain](https://img.shields.io/badge/LangChain-121D33?style=for-the-badge&logo=chainlink&logoColor=white) ![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=for-the-badge&logoColor=white) ![OpenRouter](https://img.shields.io/badge/OpenRouter-6366F1?style=for-the-badge&logoColor=white) |
| **Models & Embeddings** | ![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white) |
| **Backend & Data** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logoColor=white) pgvector |
| **Cloud & Infra** | ![Google Cloud Platform](https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white) ![Vertex AI](https://img.shields.io/badge/Vertex%20AI-34A853?style=for-the-badge&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white) |
| **UI** | ![Gradio](https://img.shields.io/badge/Gradio-FF7043?style=for-the-badge&logoColor=white) |

---

## 🌟 Featured Projects

<table>
  <tr>
    <td width="50%" align="center" style="padding: 20px;">
      <a href="https://github.com/SID-SURANGE/briefcast">
        <img width="100%" src="https://github-readme-stats.vercel.app/api/pin/?username=SID-SURANGE&repo=briefcast&theme=dark" alt="Briefcast">
      </a>
    </td>
    <td width="50%" style="padding: 20px;">
      <h3>Briefcast</h3>
      <p>Automated AI research briefing agent — monitors Google AI, DeepMind, OpenAI, Anthropic, arXiv and more, then delivers a curated daily digest to Telegram with follow-up Q&A over a 14-day rolling knowledge base.</p>
      <p><strong>Stack:</strong> FastAPI · PostgreSQL + pgvector · LangChain LCEL · OpenRouter (Gemini, Claude) · APScheduler · Railway</p>
      <p><strong>Highlights:</strong> dual-layer deduplication (SHA-256 + cosine similarity), tiered source ranking, RAG answers with citations, ~$8/month to run in production</p>
    </td>
  </tr>
  <tr>
    <td width="50%" align="center" style="padding: 20px;">
      <a href="https://github.com/SID-SURANGE/ResumeParser">
        <img width="100%" src="https://github-readme-stats.vercel.app/api/pin/?username=SID-SURANGE&repo=ResumeParser&theme=dark" alt="Resume Parser">
      </a>
    </td>
    <td width="50%" style="padding: 20px;">
      <h3>ResumeParser</h3>
      <p>HR-focused resume analysis tool that runs entirely on local LLMs — no API keys required. Extracts structured data from PDFs, flags missing sections, generates tailored interview questions, and visualizes resume content.</p>
      <p><strong>Stack:</strong> FastAPI · Gradio · PyTorch · IBM Docling · LM Studio (quantized Llama 3.1/3.2, IBM Granite)</p>
      <p><strong>Highlights:</strong> fully offline, 8-bit quantized model support, spell-check analysis, word cloud generation</p>
    </td>
  </tr>
  <tr>
    <td width="50%" align="center" style="padding: 20px;">
      <a href="https://github.com/SID-SURANGE/AI-Sandbox">
        <img width="100%" src="https://github-readme-stats.vercel.app/api/pin/?username=SID-SURANGE&repo=AI-Sandbox&theme=dark" alt="AI Sandbox">
      </a>
    </td>
    <td width="50%" style="padding: 20px;">
      <h3>PageSense · AgentForge · AI-Sandbox</h3>
      <p>Monorepo of production-grade experiments. <strong>PageSense</strong>: Chrome extension + FastAPI/Qdrant backend for semantic search over your browsing history. <strong>AgentForge</strong>: deployed agentic app with web search and image generation.</p>
      <p><strong>Stack:</strong> FastAPI · Qdrant · Gradio · smolagents · LlamaIndex · JavaScript (extension)</p>
    </td>
  </tr>
</table>

---

## ✍️ Writing

- **[Briefcast: How I Built a Personal AI Intelligence Agent That Reads the Entire AI Ecosystem — For ~$10/Month](https://medium.com/@ssurange.dev/briefcast-how-i-built-a-personal-ai-intelligence-agent-that-reads-the-entire-ai-ecosystem-for-ac0f87d4fe65)**
- **[What's new with OpenAI's gpt-4o-mini](https://medium.com/@ssurange.dev/whats-new-with-openai-s-gpt-4o-mini-97a79e6047c3)**
- **[Deciphering the power of Vision Language Models](https://medium.com/@ssurange.dev/deciphering-the-power-of-vision-language-vision-language-models-b873e06daae5)**
- **[AgentForge: A simple AI Agent with Web Search and Image Generation](https://medium.com/@ssurange.dev/agentforge-a-simple-ai-agent-with-web-search-and-image-generation-capabilities-8c756f047c05)**
- **[ProGAN, StyleGAN, StyleGAN2: Exploring NVIDIA's breakthroughs](https://medium.com/@sidsurange/c90ddb7f9b61#264d-2312224d64e4)**

---

## 🏆 Certifications

- Oracle Certified Generative AI Professional
- Google Cloud Professional Data Engineer

---

## 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=SID-SURANGE&show_icons=true&theme=radical)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=SID-SURANGE&layout=compact&theme=radical)

---

## 📫 Connect

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
