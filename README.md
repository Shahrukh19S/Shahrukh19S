## Hi, I'm Abdullah Ansari 👋

**AI/ML Engineer | Generative AI, RAG and Agentic Systems**

I take an idea, make it real, and make it succeed in production. Here that means AI systems you can run, test, and measure: advanced agentic systems with guardrails including human in the loop (HITL), RAG graded by pre-registered evaluation, and cost and latency measured, not guessed.
> A software developer at the core, I've built in Python and C++ for years and committed fully to software/CS after my Bachelor's in Electronics (2018). Working for international clients as a freelancer since 2020, and AI/ML-focused since 2024: classical machine learning and deep learning first, then LLMs, RAG, and agentic systems. Every project here is built from first principles, end to end, and published with what worked and what didn't.

## What I build
- ✔️ **Agentic AI:** provider-agnostic LLM agents and multi-agent orchestration with LangChain and LangGraph, MCP servers and clients, tool calling, and middleware guardrails (approval gates, tiered access, provider failover)
- ✔️ **RAG and retrieval:** naive, hybrid (BM25 plus RRF), and agentic RAG over vector databases, with grounded, citable answers that stay private when they need to
- ✔️ **LLMOps and MLOps:** evaluation, traceability, monitoring, benchmarking across AI providers, and measured cost and latency
- ✔️ **ML and deep-learning foundations:** classical ML, deep learning, and NLP, from data preparation and model development/training through evaluation, with leakage-safe pipelines and fine-tuned transformers

## How I build
I teach and mentor coders worldwide, from young first-timers to working adults, as a coding instructor at BrightChamps and on my YouTube channel, [BitzNTwist](https://www.youtube.com/@bitzntwist). So I build code to be learned from, not just used:

- 🔹 Readable by design: clear READMEs and comments written to teach, so anyone can follow, run, and learn from the code
- 🔹 Modular, not one-off scripts: clean structure and pinned dependencies, easy to navigate and extend
- 🔹 Honest and reproducible: real results and trade-offs stated plainly, backed by tests and pinned evaluation sets

## Featured projects

- **[adaptive-rag-docs](https://github.com/Shahrukh19S/adaptive-rag-docs):** three-mode adaptive RAG (naive, hybrid BM25 plus RRF, agentic) over 3,777 chunks of LangChain and LlamaIndex documentation, with local bge embeddings in ChromaDB and Gemini on Google Cloud Vertex AI. A router moves a question type to a lighter mode only on graded evidence; pre-registered Ragas evaluation on a verified answer key, measured spend ($0.32 to answer and $0.59 to grade a live run), a Streamlit dashboard, and 600+ tests.
- **[folio-mcp](https://github.com/Shahrukh19S/folio-mcp)**: privacy-first, provider-agnostic document Q&A: an MCP server and client (roots as a hard path guard, sampling) behind a CLI and an OAuth 2.1 web app. 5/5 grounded answers on Cerebras (~0.5s median per model call) vs 3/5 on a local 7B model (~9.5s per call).
- **[langchain-repo-radar](https://github.com/Shahrukh19S/langchain-repo-radar)**: multi-agent library scout: an orchestrator delegates to a web-search specialist and a GitHub MCP specialist, then returns a ranked, evidence-backed recommendation as structured output. Ships a public analysis of a free-tier LLM that fabricated metrics instead of calling its tool.
- **[langchain-byline](https://github.com/Shahrukh19S/langchain-byline)**: production-ready publishing agent hardened entirely by middleware: an approve/edit/reject gate before any publish, tier-locked tools behind access-code auth, thread summarization, and multi-provider failover. 1 call per plain draft, 0.59s median per draft (Cerebras).
- **[langchain-hiking-agent](https://github.com/Shahrukh19S/langchain-hiking-agent)**: hiking day-planner agent on LangChain 1.x: plans a day hike with web-grounded trail and weather search, short-term memory, typed JSON output, and multimodal gear-photo ID. The planner runs on local Ollama and swaps to any OpenAI-compatible cloud model.
- **Machine learning and deep-learning foundations:** [bert-imdb-sentiment](https://github.com/Shahrukh19S/bert-imdb-sentiment) (BERT fine-tuning in PyTorch, F1 0.83 held-out, 0.86 unseen) · [credit-risk-ml-pipeline](https://github.com/Shahrukh19S/credit-risk-ml-pipeline) (leakage-safe XGBoost, ROC AUC 0.737 with a tuned operating point) · [covid-topic-modeling-faiss](https://github.com/Shahrukh19S/covid-topic-modeling-faiss) (LDA topics with FAISS semantic search)

## Skills and tech stack
- **Agents and LLMs:** LLM agents, multi-agent systems, LLM frameworks (LangChain, LangGraph, LlamaIndex, PydanticAI), MCP (servers and clients), tool calling, human-in-the-loop (HITL), structured outputs, context engineering, monitoring and observability
- **RAG and Retrieval:** RAG (hybrid, agentic), vector databases (ChromaDB, FAISS), embeddings, BM25 with reciprocal rank fusion, cross-encoder reranking, LLM and RAG evaluation (Ragas)
- **ML and Deep Learning:** PyTorch, TensorFlow/Keras, scikit-learn, XGBoost, neural networks, deep learning, NLP, transformers (BERT fine-tuning), Hugging Face
- **Cloud and Model Platforms:** Google Cloud (GCP), Vertex AI, Gemini, AWS, Azure, LiteLLM, local LLMs (LM Studio, Ollama, GGUF, llama.cpp, vLLM)
- **Programming and Tools:** Python, C++, FastAPI, REST APIs, OAuth 2.1, Streamlit, Docker, CI/CD, pytest, Git and GitHub

## Certifications
- **LangChain Academy:** [Foundation: Introduction to LangChain - Python (2026)](https://academy.langchain.com/certificates/w6ajsorbyy)
- **Google Cloud:** [Introduction to AI and Machine Learning on Google Cloud](https://www.skills.google/public_profiles/5bfd26c0-d3ac-4e49-a82e-4c287cd90ffa/badges/27511299) (course completion, 2026)
- **Anthropic:** [Model Context Protocol: Advanced Topics](https://verify.skilljar.com/c/jii9hep3nqe9) · [Introduction to Model Context Protocol](https://verify.skilljar.com/c/gf6s62tfgfqn) · [Introduction to Agent Skills](https://verify.skilljar.com/c/oy5kqw8zofmz) · [Introduction to Subagents](https://verify.skilljar.com/c/3f8jq2buypbr) · [Claude Code in Action](https://verify.skilljar.com/c/iar6emp3xkm8) · [Claude Code 101](https://verify.skilljar.com/c/wu7p4soaq3p9)

## Connect

- 💼 LinkedIn: [@abd-ansari](https://www.linkedin.com/in/abd-ansari)
- ▶️ YouTube: [@bitzntwist](https://www.youtube.com/@bitzntwist)
- 🧑‍💻 Upwork: [Hire me on Upwork](https://www.upwork.com/freelancers/~01713b0601d1d90c57)
- 🌐 Google Developer profile: [@AbdAnsari](https://g.dev/AbdAnsari)
