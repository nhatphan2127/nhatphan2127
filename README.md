<h1 align="center">Phan Minh Nhật</h1>

<p align="center">
  <b>AI Engineer · LLM & RAG Systems · Backend Developer</b>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/nh%E1%BA%ADt-phan-minh-530153400/">LinkedIn</a>
  ·
  <a href="mailto:nhatphan2127@gmail.com">Email</a>
  ·
  Ho Chi Minh City, Vietnam
</p>

> **👋 About Me**: Computer Science student at **Ton Duc Thang University (TDTU)** (2023 – 2027), focused on **Natural Language Processing** and **Large Language Models**. I build RAG and LLM-powered systems end to end, from hybrid retrieval and fine-tuning to the APIs and containers that serve them.
>
> 📐 **Core Principle**: *"Retrieve → Ground → Evaluate"*: every answer should be backed by evidence, and every system should be measured.

## Selected Work

### ⚖️ [Vietnamese Traffic Law AI Advisor](https://github.com/nhatphan2127/traffic-laws-AI-advisor)
RAG-based assistant that answers Vietnamese traffic law questions with context-grounded responses and legal citations.
- Hybrid retrieval pipeline: dense vector search + BM25, query normalization, and legal cross-reference expansion.
- Model Context Protocol (MCP) integration and guardrails for controlled, reliable LLM interactions.
- **Results (100 legal queries):** Recall@5 **0.743** · MRR **0.8495** · Final Recall **0.935** after reference expansion.

`FastAPI` `Qdrant` `Ollama` `Hugging Face` `MCP` `ReactJS` `Docker`

### 🍜 [Vietnamese Visual Question Answering (VQA)](https://github.com/nhatphan2127/multiple-VQA-model-comparison)
Domain-specific Vietnamese VQA system for food images, comparing CNN-based and multimodal architectures.
- Dataset of **3,600+ QA pairs** and **11,000+ augmented samples**, with data collection supported by Google APIs.
- Compared ResNet + PhoBERT (LSTM / Transformer decoders) against **Qwen2-VL**.
- Fine-tuned multimodal LLMs with **SFT** and **DPO**; evaluated with BLEU, ROUGE-L, BERTScore, VQA Accuracy, and LLM-as-a-Judge.

`PyTorch` `Hugging Face` `Qwen2-VL` `SFT` `DPO` `Gradio`

### 📚 [Inkverse: Comic Reading Platform](https://github.com/nhatphan2127/comic-app)
Full-stack comic platform with ratings, reading history, rankings, and personalized recommendations.
- Hybrid recommender: user-based collaborative filtering + TF-IDF / cosine-similarity content filtering, with cold-start handling.
- Versioned REST APIs with OpenAPI 3.1, RFC 9457 error responses, session auth, and RBAC.
- 30-table relational schema with transactions and soft deletion (controller–service–repository).

`Node.js` `Express` `Sequelize` `SQLite` `React` `TypeScript` `OpenAPI`

### 📝 [Collaborative Note-Taking App](https://github.com/nhatphan2127/note-app-web)
Real-time note-taking web app with labels, image uploads, password-protected notes, and permission-based sharing.
- Laravel Sanctum authentication with email verification and password recovery.
- Real-time collaboration via Laravel Reverb and WebSockets.
- Dockerized multi-service setup: Nginx, MySQL, Redis, and queue workers.

`Laravel` `MySQL` `Redis` `WebSockets` `React` `TypeScript` `Docker`

## Tech Stack

| Domain | Technologies | Focus Areas |
|---|---|---|
| **LLM & RAG** | LangChain · LangGraph · Ollama · Qdrant · BM25 · MCP | Hybrid retrieval · AI agents · Tool calling · Guardrails · Prompt engineering |
| **Deep Learning** | PyTorch · Hugging Face · LoRA / QLoRA · Gradio | Fine-tuning (SFT, DPO) · Multimodal models · Evaluation |
| **Backend** | FastAPI · Node.js / Express · Laravel · REST · OpenAPI | Model serving · Authentication · RBAC · WebSockets |
| **Data & DevOps** | MySQL · MongoDB · SQLite · Redis · Docker · Nginx | Relational design · Containerization · GitHub / GitLab |
| **Frontend** | React · TypeScript | Interfaces for AI and web applications |

## GitHub Activity

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=nhatphan2127&show_icons=true&hide_border=true" height="165" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=nhatphan2127&layout=compact&hide_border=true" height="165" alt="Top languages" />
</div>


<p align="center">
  🔎 Open to <b>AI Engineer</b> internship opportunities · <a href="mailto:nhatphan2127@gmail.com">nhatphan2127@gmail.com</a>
</p>
