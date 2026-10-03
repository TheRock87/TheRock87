### Hossam El-Kharbotly: Building Sovereign, Scalable AI Systems

AI Engineer at Dar Al-Handasah. I build LLM agents that take real actions, and I design and run the fully on-premise LLM stack they live on: open-weight models, served in-house, with no confidential data leaving the firm.

**Portfolio:** [therock87.github.io](https://therock87.github.io) · **LinkedIn:** [linkedin.com/in/hossam87](https://www.linkedin.com/in/hossam87) · **Email:** hossam.kharbotly@gmail.com

---

#### What I build

- **Multi-agent systems in production.** Agents that replace manual research for cost engineering and other departments, used by hundreds of users across 3 departments. A historic-cost lookup that took a cost engineer up to half a day now returns a full benchmark and comparison in minutes.
- **On-premise LLM serving.** Reasoning, embedding and reranking models (open-weight Qwen-family) on vLLM and TEI, with LiteLLM as the gateway for model routing, personal API keys and per-user budgets. Hundreds of concurrent users at peak, 100K+ requests at an error rate under 2%, several models co-located per GPU, months without OOM, across Azure A100 VMs and on-premise GPUs.
- **Human-in-the-loop agents.** An interrupt pipeline that lets an agent pause its own workflow to resolve ambiguity or ask for missing context before answering, generalized into a shared platform capability so every new agent inherits it.
- **Document intelligence.** The firm's first document-digitization platform: region-level routing between VLM-based OCR and classical OCR turns a 3,500-page document into structured, searchable data in about 25 minutes, around 100 files a day.
- **Observability and self-healing.** Langfuse agent tracing, Prometheus, Grafana and Loki telemetry, and an auto-heal layer that restarts failed services.

#### Selected work

| Project | What it is |
|---|---|
| [BoQ Cost Agent v2](https://therock87.github.io/#p-boq-cost-agent-v2) | Harness-engineered cost agent with a toolset of 6 tools (code-style search plus embeddings over full item descriptions). Every answer carries a trail (which BoQ, which project, which year) and degrades through a defined fallback ladder instead of failing. |
| [BoQ Cost Agent v1](https://therock87.github.io/#p-boq-cost-agent) | LangGraph pipeline of typed nodes with a fix-agent, an LLM ambiguity grader, and typed human-in-the-loop interrupts over a 1.2M-row historic cost database. |
| [Enterprise Knowledge Base](https://therock87.github.io/#p-enterprise-knowledge-base) | On-premise retrieval over internal reports, specifications and standards: hybrid Weaviate, Neo4j and MongoDB, open-weight models on internal GPUs. |
| [Adaptive Learning Platform](https://therock87.github.io/#p-adaptive-learning-platform) | Knowledge-graph and LLM orchestration that turns documents, videos and web content into personalized learning roadmaps; 12+ REST endpoints at under 100 ms P95, 97+ automated tests. |
| [Arabic Podcast Semantic Search](https://therock87.github.io/#p-arabic-podcast-search) | Whisper transcription, LLM-cleaned transcripts, MiniLM embeddings and FAISS search with timestamp deep links: 18 episodes (~20 hours) into ~7.6k paragraph embeddings, 50 ms median CPU search latency. |
| [El-Mal El-Halal subtitles dataset](https://huggingface.co/datasets/hossam87/el-mal-el-halal-podcast-subtitles) | Cleaned Arabic podcast subtitles released on Hugging Face for Arabic ASR and NLP. |

#### Stack

- **Languages:** Python, TypeScript, C++, SQL, Cypher
- **Agents and LLMs:** LangChain/LangGraph, deepagents, DSPy, Hugging Face Transformers, OpenAI API, harness engineering, human-in-the-loop pipelines, text-to-SQL, RAG, GraphRAG, golden-set evaluation
- **Serving and infra:** vLLM, TEI, LiteLLM, Docker, Azure, Azure AI Foundry, AWS (EC2, S3), GitHub Actions, MinIO
- **Observability:** Langfuse, Prometheus, Grafana, Loki, OpenTelemetry, MLflow
- **Data and retrieval:** Weaviate, Neo4j, MongoDB, SQL Server, PostgreSQL, Qdrant, FAISS
- **Documents and Arabic:** VLM and classical OCR, Arabic NLP, Arabic semantic search, Whisper
- **ML:** PyTorch, TensorFlow, Keras, scikit-learn

#### Contact

Cairo-based, currently on assignment in Amman, Jordan. Open to relocation (UAE first) and remote.
Reach me at hossam.kharbotly@gmail.com or on [LinkedIn](https://www.linkedin.com/in/hossam87).
