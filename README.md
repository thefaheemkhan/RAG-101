# 🧠 AI Engineer Project Bible — 2026
### *Build things companies already need.*

> 42 practical projects — from your first deployed chatbot to full research reimplementations.  
> Every project is monetizable, teaches a real skill, and signals something specific to employers.  
> Sorted by difficulty. Tied to papers where relevant.

---

## 📊 At a Glance

| Stat | Count |
|------|-------|
| 🗂️ Projects Total | 42 |
| 📄 Research Papers | 12 |
| 🏭 Industry Verticals | 6 |
| 🚫 Excuses Accepted | $0 |

---

## 🗺️ Directory

- [01 — Foundation Projects (Beginner)](#01--foundation-projects-beginner)
- [02 — Production-Grade Projects (Intermediate)](#02--production-grade-projects-intermediate)
- [03 — Advanced System Projects (Advanced)](#03--advanced-system-projects-advanced)
- [04 — Research Reimplementations](#04--research-reimplementations)
- [05 — Industry Verticals](#05--industry-verticals)

---

## Legend

| Badge | Meaning |
|-------|---------|
| 🟢 Beginner | 2–4 weeks each |
| 🔵 Intermediate | 4–8 weeks each |
| 🔴 Advanced | 6–16 weeks each |
| 🟣 Research | Paper + implementation + writeup |
| 🟡 Monetizable | Has a clear path to revenue |

---

## 01 — Foundation Projects (Beginner)

> Start here. Each project takes 2–4 weeks, teaches a foundational skill, and is directly monetizable.

---

### P-01 · Document Q&A Chatbot (RAG over your own PDFs)
🟢 Beginner · 🟡 Monetizable · ⏱ 2–3 weeks

Upload any PDF, ask questions, get cited answers. Think "ChatPDF" but you built it and control it. Works for legal docs, contracts, manuals.

> Every SMB has documents they can't search. This is a real SaaS product. Law firms, HR teams, and consultants pay for this today.

**Stack:** `Python` `Claude API` `LangChain` `ChromaDB` `Streamlit`  
**Revenue:** $29–99/mo SaaS · Freelance $500–2k

---

### P-02 · AI Customer Support Bot with Escalation
🟢 Beginner · 🟡 Monetizable · ⏱ 2–3 weeks

A support bot trained on your FAQ, product docs, and past tickets. Knows when to escalate to a human. Tracks what it can't answer.

> Every e-commerce store and SaaS product needs this. The escalation logic and "I don't know" tracking is what separates a real product from a toy.

**Stack:** `Python` `FastAPI` `Claude API` `Pinecone` `Slack/Webhook`  
**Revenue:** $199–499/mo per client · Agency play

---

### P-03 · Meeting Transcription + Action Items Extractor
🟢 Beginner · ⏱ 1–2 weeks

Paste or upload a meeting transcript. Get structured summary, decisions made, action items with owners, and open questions. Exports to Notion/Slack.

> Shows you can handle structured output engineering — one of the most in-demand practical LLM skills.

**Stack:** `Python` `Whisper` `Claude API` `Pydantic` `Notion API`  
**Revenue:** Internal tool / B2B pilot

---

### P-04 · Resume + Job Description Match Scorer
🟢 Beginner · 🟡 Monetizable · ⏱ 2 weeks

Upload a resume and paste a JD. Get a fit score, gap analysis, suggested rewrites, and keywords to add. Batch mode for 50+ JDs at once.

> Recruiting and career coaching market. Batch mode + API makes it B2B. Outplacement firms, recruiters, and bootcamps pay for this.

**Stack:** `Python` `Claude API` `PyPDF2` `FastAPI` `React`  
**Revenue:** $9–29/mo consumer · $500/mo B2B bulk

---

### P-05 · LLM Cost & Latency Benchmarking Dashboard
🟢 Beginner · ⏱ 2 weeks

Run identical prompts across Claude, GPT-4, Gemini, Llama. Measure tokens/sec, cost per 1k tokens, quality scores. Live dashboard with filters.

> Signals eval engineering skills. Interviewers love seeing this — it shows you think about production costs, not just "does it work." Publish the benchmarks publicly for SEO.

**Stack:** `Python` `Multiple APIs` `Plotly Dash` `SQLite` `GitHub Actions`  
**Revenue:** Open source → consulting leads

---

### P-06 · AI Email Responder (Gmail + Tone Control)
🟢 Beginner · 🟡 Monetizable · ⏱ 2–3 weeks

Connect to Gmail. Classify incoming emails by urgency and type. Draft responses in your tone. One-click send. Works with your contact history as context.

> Real workflow automation for executives and solopreneurs. Tone matching requires context engineering — a core skill to demonstrate.

**Stack:** `Python` `Gmail API` `Claude API` `OAuth2` `Flask`  
**Revenue:** $19/mo consumer · White-label B2B

---

### P-07 · Prompt Evaluation Harness (Your Own PromptFoo)
🟢 Beginner · ⏱ 2–3 weeks

Build a CLI tool that runs a test suite of prompts against an LLM, scores outputs on custom criteria (factual, format, tone), and diffs results across model versions.

> This IS the job. Any team running LLMs in prod needs this. Building it from scratch shows you understand why evals matter, not just how to use a library.

**Stack:** `Python` `Typer CLI` `Claude API` `YAML configs` `Rich`  
**Revenue:** Open source credibility project

---

### P-08 · AI SEO Content Brief Generator
🟢 Beginner · 🟡 Monetizable · ⏱ 2 weeks

Input a keyword. Scrape top 10 SERPs. Analyze structure, headings, word count. Generate a content brief with outline, entities to cover, questions to answer.

> Content agencies pay $50–200 per manual brief. Automate that. Real business with clear ROI. Teaches web scraping + LLM synthesis pipeline.

**Stack:** `Python` `BeautifulSoup` `SerpAPI` `Claude API` `FastAPI`  
**Revenue:** $49–199/mo · Agency white-label

---

## 02 — Production-Grade Projects (Intermediate)

> These projects take 4–8 weeks each and represent what companies actually hire for. Each one could be sold as a standalone product.

---

### P-09 · Multi-Source Research Agent
🔵 Intermediate · 🟡 Monetizable · ⏱ 4–5 weeks

Agent that takes a research question, searches web + arxiv + PubMed, deduplicates sources, synthesizes findings, and produces a cited report with confidence scores.

> Demonstrates the full agent loop — planning, tool use, source evaluation, synthesis. Sellable to consulting firms, law firms, pharma.

**Stack:** `Python` `Claude API` `Tavily Search` `ArXiv API` `LangGraph` `FastAPI`  
**Revenue:** $99–499/mo per team · Consulting

---

### P-10 · AI Code Review Bot (GitHub Actions Integration)
🔵 Intermediate · 🟡 Monetizable · ⏱ 4–6 weeks

GitHub Action that triggers on every PR. Reviews code for bugs, security issues, style violations, and complexity. Comments inline. Learns from approvals over time.

> Every engineering team wants this. GitHub Actions integration is the key — it fits existing workflow. Sell as a GitHub App.

**Stack:** `Python` `GitHub API` `Claude API` `GitHub Actions` `Docker`  
**Revenue:** $29–199/mo per repo · $0 OSS tier

---

### P-11 · Legal Contract Analyzer & Risk Flagging
🔵 Intermediate · 🟡 Monetizable · ⏱ 5–7 weeks

Upload any contract. Extract key clauses, flag unusual or risky terms, compare against standard templates, summarize obligations by party. Export redline suggestions.

> NDA review alone is a $500–2k/hr lawyer task. Startups and SMBs desperately need affordable contract review.

**Stack:** `Python` `Claude API` `LangChain` `pgvector` `FastAPI` `React`  
**Revenue:** $199–999/mo · Law firm white-label

---

### P-12 · RAG Evaluation Pipeline with RAGAS + Custom Metrics
🔵 Intermediate · ⏱ 4–5 weeks

Build a full eval pipeline: generate test Q&A from your corpus, run retrieval, score with RAGAS (faithfulness, context recall, answer relevancy), track regressions in CI/CD.

> This is the project that gets you hired as a senior AI engineer. Most teams have RAG. Almost none have evals. Showing this in an interview ends the technical bar.

**Stack:** `Python` `RAGAS` `LangChain` `Pinecone` `GitHub Actions` `MLflow`  
**Revenue:** Career signal — gets you hired

---

### P-13 · E-commerce Product Description Generator at Scale
🔵 Intermediate · 🟡 Monetizable · ⏱ 4–5 weeks

Input: product specs CSV. Output: SEO-optimized descriptions, bullet points, A/B variants, translated to 5 languages. Batch 10k products with quality scoring per output.

> Shopify merchants, Amazon sellers, manufacturing companies all have this problem. The batch + quality scoring at scale is the differentiator.

**Stack:** `Python` `Claude API (Batch)` `Celery` `Redis` `FastAPI` `Postgres`  
**Revenue:** $0.10–0.50 per product · Agency model

---

### P-14 · HR Policy Q&A Bot with Source Citations + Audit Log
🔵 Intermediate · 🟡 Monetizable · ⏱ 5–6 weeks

Ingests employee handbook, HR policies, benefits docs. Employees ask questions. Bot answers with policy citations. Logs every Q&A for HR audit. Escalates when unsure.

> HRIS vendors charge $50k+/year for this. Mid-market companies (200–2000 employees) are underserved. The audit log is what makes this enterprise-ready.

**Stack:** `Python` `Claude API` `Weaviate` `FastAPI` `Postgres` `Slack SDK`  
**Revenue:** $500–5k/mo per company

---

### P-15 · Structured Data Extraction Pipeline (Invoices, Receipts, Forms)
🔵 Intermediate · ⏱ 4–5 weeks

Upload any document — invoice, receipt, form, medical record. Extract structured JSON with 98%+ accuracy. Handle tables, handwriting, multiple layouts.

> Accounts payable automation alone is a billion-dollar market. Vision + structured output is the technical skill. Teaches you multimodal document AI.

**Stack:** `Python` `Claude Vision` `Pydantic` `FastAPI` `S3` `Postgres`  
**Revenue:** $0.05–0.20/doc · ERP integration play

---

### P-16 · AI Sales Call Analyzer (Transcription + Coaching)
🔵 Intermediate · 🟡 Monetizable · ⏱ 5–7 weeks

Upload sales call recordings. Transcribe with speaker diarization. Score against sales framework (MEDDIC, SPIN). Extract objections, next steps, coaching feedback per rep.

> Sales coaching software is $50k+/yr enterprise. This competes on price and AI quality. Revenue intelligence is a hot space in 2026.

**Stack:** `Python` `Whisper` `Claude API` `pyannote` `FastAPI` `React`  
**Revenue:** $99–499/mo per team

---

### P-17 · Knowledge Base Auto-Updater from Slack/Confluence
🔵 Intermediate · 🟡 Monetizable · ⏱ 5–6 weeks

Monitor Slack channels and Confluence pages. When something new is discussed or decided, auto-draft knowledge base updates, flag gaps, remove outdated entries.

> Documentation rot is universal. This solves it automatically. Teaches real-time pipeline design, webhook processing, and knowledge graph maintenance.

**Stack:** `Python` `Slack Events API` `Confluence API` `Claude API` `Celery`  
**Revenue:** $299–999/mo per workspace

---

### P-18 · Local LLM Deployment with OpenAI-Compatible API
🔵 Intermediate · ⏱ 4–6 weeks

Deploy Llama 3 or Mistral locally using vLLM. Expose an OpenAI-compatible REST API. Add prompt caching, rate limiting, token counting, and a usage dashboard.

> Data-sensitive companies (healthcare, legal, finance) cannot use cloud APIs. Building this proves you can handle on-prem AI deployments — a premium consulting use case.

**Stack:** `Python` `vLLM` `FastAPI` `Docker` `Prometheus` `Grafana`  
**Revenue:** Consulting: $5–15k deployment

---

## 03 — Advanced System Projects (Advanced)

> These are 6–16 week projects. Completing even one puts you in the top 10% of AI engineers. These are real products.

---

### P-19 · Multi-Agent Workflow Engine (LangGraph / Custom)
🔴 Advanced · 🟡 Monetizable · ⏱ 8–12 weeks

Build a general-purpose multi-agent engine. Agents for research, writing, coding, fact-checking, critique. Orchestrator assigns tasks, checks results, retries on failure. Human checkpoints configurable.

> This is the core of every AI product company right now. Understanding orchestration patterns, failure modes, and inter-agent communication is what senior AI engineers are paid for.

**Stack:** `Python` `LangGraph` `Claude API` `Redis` `Postgres` `FastAPI` `Temporal`  
**Revenue:** B2B platform $1k–10k/mo · VC-fundable

---

### P-20 · Domain-Specific Fine-Tuned Model (Medical / Legal / Finance)
🔴 Advanced · 🟡 Monetizable · ⏱ 8–10 weeks

Fine-tune Llama 3 or Mistral 7B on domain-specific data using QLoRA. Build eval harness comparing fine-tuned vs base vs GPT-4. Deploy adapter with A/B testing. Write up the results.

> Proves you can go below the API layer. Medical, legal, and finance verticals have specialized vocabulary and reasoning patterns that base models fail at.

**Stack:** `Python` `Hugging Face` `QLoRA` `unsloth` `RAGAS` `vLLM` `W&B`  
**Revenue:** Sell the adapter · Vertical SaaS play

---

### P-21 · Real-Time Voice AI Agent (Sub-800ms Latency)
🔴 Advanced · 🟡 Monetizable · ⏱ 8–12 weeks

End-to-end voice agent: Whisper STT → LLM reasoning → ElevenLabs TTS. Sub-800ms perceived latency via streaming. Add persona, memory of past calls, tool access.

> Voice AI is the next UI wave. Phone agents for appointment booking, customer service, and surveys are replacing traditional IVR. Latency is the hard technical problem.

**Stack:** `Python` `Whisper` `Claude API` `ElevenLabs` `Pipecat` `WebSockets` `FastAPI`  
**Revenue:** $0.10/min · $500–2k/mo per client

---

### P-22 · Hallucination Detection & Guardrails System
🔴 Advanced · ⏱ 8–10 weeks

Build a system that detects hallucinations in LLM output by cross-referencing source documents, runs factual consistency checks, and applies configurable guardrails before output is shown to users.

> AI safety/reliability is the #1 blocker for enterprise adoption. Building a working hallucination detector is a research-adjacent skill that signals serious engineering depth.

**Stack:** `Python` `NLI models` `Claude API` `BLEURT` `Prometheus` `FastAPI`  
**Revenue:** Enterprise middleware · Safety layer SaaS

---

### P-23 · Autonomous Coding Agent (GitHub Issue → PR)
🔴 Advanced · 🟡 Monetizable · ⏱ 10–14 weeks

Agent reads GitHub issues, writes code, runs tests, fixes failures, opens a PR with explanation. Handles simple bugs and feature additions. Human reviews the PR.

> This is literally what GitHub Copilot Workspace, Devin, and Claude Code are. Building your own version teaches you agent architecture at its hardest — real code execution, error recovery.

**Stack:** `Python` `Claude API` `GitHub API` `Docker (sandboxed exec)` `LangGraph` `pytest`  
**Revenue:** OSS → consulting · $1–5k/mo per team

---

### P-24 · AI-Powered BI Dashboard (Natural Language → SQL → Chart)
🔴 Advanced · 🟡 Monetizable · ⏱ 8–12 weeks

Connect to any Postgres/MySQL DB. Ask "Show me revenue by region last quarter." Get SQL, chart, and plain-English explanation. Learns your schema over time. Flags suspicious queries.

> Text-to-SQL is one of the hottest LLM application areas. Every BI tool is adding this. Building your own proves you understand the schema injection, disambiguation, and SQL safety problems.

**Stack:** `Python` `Claude API` `SQLAlchemy` `Plotly` `FastAPI` `React` `pgvector`  
**Revenue:** $299–2k/mo per company

---

### P-25 · Personalized AI Tutor with Adaptive Learning
🔴 Advanced · 🟡 Monetizable · ⏱ 10–14 weeks

Tutoring system that builds a knowledge model of the student, identifies gaps, generates targeted questions, adjusts difficulty, tracks mastery over time. For any subject domain.

> EdTech is a massive market. Adaptive learning systems are extremely hard to build well. The memory architecture — tracking per-concept mastery — is the technical challenge here.

**Stack:** `Python` `Claude API` `Postgres` `Knowledge graph` `FastAPI` `React`  
**Revenue:** $29/mo consumer · $5k/mo school license

---

### P-26 · Production LLMOps Platform (Monitoring + Tracing)
🔴 Advanced · ⏱ 10–14 weeks

Self-hosted LLMOps dashboard: log every LLM call with latency, cost, prompt, output. Trace multi-step chains. Alert on regressions. Compare prompts A/B. Replay failed calls.

> Langfuse and Helicone exist but building this yourself shows you understand the whole observability stack. Companies with internal models need self-hosted solutions for data privacy.

**Stack:** `Python` `OpenTelemetry` `ClickHouse` `FastAPI` `React` `Docker`  
**Revenue:** Open source → enterprise support deals

---

### P-27 · Synthetic Training Data Generator with Quality Filtering
🔴 Advanced · 🟡 Monetizable · ⏱ 6–8 weeks

Given a task and a few examples, generate thousands of high-quality training examples. Auto-filter with LLM-as-judge. Output in any fine-tuning format. Dedup and diversity checks.

> Data is the bottleneck for every fine-tuning project. A pipeline that generates + validates synthetic data is directly monetizable to any team doing model training.

**Stack:** `Python` `Claude API` `Sentence-transformers` `Pandas` `FastAPI` `MinIO`  
**Revenue:** $0.001/example at scale · MLOps tool

---

### P-28 · AI Due Diligence Tool for Investors (Company Research Agent)
🔴 Advanced · 🟡 Monetizable · ⏱ 10–14 weeks

Input a company name. Agent pulls Crunchbase, LinkedIn, news, filings, reviews, patents, GitHub activity. Produces structured DD report: team, market, competition, risks, red flags.

> VC analysts spend 40+ hours on early DD. This compresses it to 2 hours of validation. VCs, PE firms, and M&A teams pay $5k–50k for comprehensive DD reports.

**Stack:** `Python` `LangGraph` `Claude API` `Crunchbase API` `SerpAPI` `Postgres`  
**Revenue:** $500–5k per report · $2k/mo subscription

---

### P-29 · Multimodal Product Catalog AI (Vision + Search + Rec)
🔴 Advanced · 🟡 Monetizable · ⏱ 8–10 weeks

Upload product images. Auto-generate titles, descriptions, tags using vision. Build semantic search over visual + text embeddings. Add "similar products" and "complete the look" recommendations.

> E-commerce companies with 10k+ SKUs have a catalog management nightmare. Vision + multimodal search is a concrete, deployable solution with clear ROI.

**Stack:** `Python` `Claude Vision` `Weaviate` `CLIP embeddings` `FastAPI` `React`  
**Revenue:** $0.01/product + $999/mo SaaS

---

### P-30 · GraphRAG: Knowledge Graph-Augmented Retrieval System
🔴 Advanced · ⏱ 8–10 weeks

Build a retrieval system where entities and relationships are extracted into a knowledge graph (Neo4j). Queries traverse the graph + vector search. Compare quality vs naive RAG with eval suite.

> GraphRAG is Microsoft's published approach and represents the frontier of production RAG. Building and benchmarking it shows you're tracking the state-of-the-art, not just using last year's patterns.

**Stack:** `Python` `Neo4j` `LangChain` `Claude API` `Pinecone` `RAGAS`  
**Revenue:** Research portfolio + consulting

---

## 04 — Research Reimplementations

> Read the original paper. Implement the core contribution. Build something usable on top. Write a blog post explaining what you learned.  
> This combination — **paper + implementation + product + writeup** — is the research portfolio signal that opens doors to AI labs and frontier teams.

---

### R-01 · RAPTOR: Recursive Abstractive Processing for Tree-Organized Retrieval
🟣 Research · *Sarthi et al., Stanford · 2024 · arxiv:2401.18059*

Standard RAG chunks documents linearly. RAPTOR clusters + recursively summarizes chunks into a tree — enabling queries at multiple abstraction levels. Dramatically outperforms naive RAG on multi-hop questions.

**Build on top:** Implement RAPTOR indexing over a large document corpus (legal cases, academic papers, product manuals). Compare retrieval quality with standard RAG using RAGAS. Add a UI showing the tree structure. Write a blog post with benchmarks.

**Stack:** `Python` `UMAP` `GMM clustering` `Claude API` `ChromaDB` `RAGAS`  
**Signal:** RAG depth + research implementation

---

### R-02 · Self-RAG: Learning to Retrieve, Generate, and Critique
🟣 Research · *Asai et al., UW · 2023 · arxiv:2310.11511*

Instead of always retrieving, Self-RAG trains the model to decide when to retrieve and to critique its own outputs using special reflection tokens. Outperforms standard RAG by large margins on factual tasks.

**Build on top:** Replicate the inference loop (retrieval decision + critique tokens) using prompt engineering with a strong base model. Apply to a medical QA task. Measure hallucination rate vs standard RAG.

**Stack:** `Python` `Claude API` `Pinecone` `BioASQ dataset` `RAGAS`  
**Signal:** Agentic RAG + self-critique patterns

---

### R-03 · HyDE: Hypothetical Document Embeddings for Dense Retrieval
🟣 Research · *Gao et al., CMU · 2022 · arxiv:2212.10496*

Instead of embedding the query directly, generate a hypothetical answer first, embed that, and use it for retrieval. Bridges the gap between query and document embedding spaces — especially for sparse queries.

**Build on top:** Implement HyDE retrieval and compare vs standard embedding retrieval on 3 datasets. Add it as a toggle in a RAG API so users can A/B test. Benchmark latency tradeoff vs quality gain.

**Stack:** `Python` `Claude API` `SentenceTransformers` `FAISS` `BEIR benchmark`  
**Signal:** Retrieval engineering depth

---

### R-04 · ReAct: Synergizing Reasoning and Acting in Language Models
🟣 Research · *Yao et al., Princeton · 2022 · arxiv:2210.03629*

ReAct alternates between reasoning traces ("Thought:") and external actions ("Action:") in a single prompt loop. It's the foundational paper behind most modern agent frameworks including LangChain's agent executor.

**Build on top:** Implement ReAct from scratch (no LangChain). Apply to a real tool-using task (web search + calculator + code execution). Compare against Chain-of-Thought without actions. Deploy as a demo showing the trace.

**Stack:** `Python` `Claude API` `Tavily` `Raw prompting` `FastAPI`  
**Signal:** Agent architecture from first principles

---

### R-05 · Constitutional AI: Harmlessness from AI Feedback
🟣 Research · *Bai et al., Anthropic · 2022 · arxiv:2212.08073*

Constitutional AI uses a set of principles to have the model critique and revise its own outputs, then RLAIF (RL from AI Feedback) instead of RLHF. This is how Claude is aligned. Understanding this is understanding frontier alignment.

**Build on top:** Implement a Constitutional AI critique-revision loop for a content moderation use case. Define a constitution of 10 principles. Measure how outputs change across revision rounds. Compare to RLHF fine-tuned baselines.

**Stack:** `Python` `Claude API` `Hugging Face` `Custom eval suite` `Weights & Biases`  
**Signal:** Alignment + safety engineering depth

---

### R-06 · Lost in the Middle: LLM Attention Patterns in Long Contexts
🟣 Research · *Liu et al., Stanford · 2023 · arxiv:2307.03172*

LLMs systematically underperform when relevant information is in the middle of a long context. This paper identifies the pattern and explains why. Has direct implications for RAG chunk ordering and context window design.

**Build on top:** Reproduce the key finding on a modern long-context model. Build a RAG system that deliberately reorders context to place most-relevant chunks at the start and end. Measure quality improvement with RAGAS.

**Stack:** `Python` `Claude API` `LangChain` `RAGAS` `Jupyter`  
**Signal:** Context engineering at research depth

---

### R-07 · RLHF: Learning to Summarize from Human Feedback
🟣 Research · *Stiennon et al., OpenAI · 2020 · arxiv:2009.01325*

The original RLHF paper applied to summarization. Human preferences train a reward model; PPO optimizes the LLM against it. This pipeline is the foundation of GPT-4, Claude, and Gemini.

**Build on top:** Implement a simplified RLHF loop: collect preference data on summaries, train a reward model, use it to score and rank outputs. Show how preference training shifts output quality even without full PPO.

**Stack:** `Python` `Hugging Face` `TRL library` `Pandas` `Weights & Biases` `GPU`  
**Signal:** Alignment pipeline from scratch

---

### R-08 · Attention Is All You Need (Transformer Architecture)
🟣 Research · *Vaswani et al., Google · 2017 · arxiv:1706.03762*

The paper that started everything. Multi-head self-attention, positional encoding, encoder-decoder architecture. Every LLM running today is a descendant of this architecture.

**Build on top:** Implement a minimal transformer from scratch in PyTorch (no libraries). Train it on a small dataset (character-level Shakespeare or code). Visualize attention heads. Write a technical post explaining each component.

**Stack:** `Python` `PyTorch` `Matplotlib` `Jupyter` `GPU`  
**Signal:** Foundational architecture knowledge — rare and impressive

---

### R-09 · Chain-of-Thought Prompting Elicits Reasoning in LLMs
🟣 Research · *Wei et al., Google · 2022 · arxiv:2201.11903*

Shows that providing step-by-step reasoning examples in prompts dramatically improves LLM performance on complex reasoning tasks. Foundation for everything from zero-shot CoT to tree-of-thought approaches.

**Build on top:** Implement and benchmark zero-shot CoT, few-shot CoT, and Tree-of-Thoughts on a hard reasoning task (GSM8K math, LSAT). Build a prompt engineering playground where users can see reasoning quality change with each technique.

**Stack:** `Python` `Claude API` `GSM8K dataset` `Streamlit` `Pandas`  
**Signal:** Prompt engineering at research depth

---

### R-10 · Toolformer: Language Models Can Teach Themselves to Use Tools
🟣 Research · *Schick et al., Meta · 2023 · arxiv:2302.04761*

Toolformer teaches LLMs to decide when and how to call APIs (calculator, search, calendar) by self-supervising on when tool calls improve prediction. It's the conceptual ancestor of all function-calling APIs.

**Build on top:** Implement the Toolformer data generation pipeline (self-supervised tool annotation). Apply to 3 tools. Compare vs standard function-calling in accuracy and tool selection precision. Publish the annotated dataset.

**Stack:** `Python` `Hugging Face` `Custom tools` `Pandas` `Claude API`  
**Signal:** Tool use + agent foundations

---

### R-11 · Mixture of Experts (MoE): From Dense to Sparse Models
🟣 Research · *Shazeer et al., Google · 2017 + Mixtral 2024 · arxiv:2401.04088*

MoE routes each token to only a subset of "expert" feed-forward networks, enabling massive parameter counts with constant compute per token. Mixtral, DeepSeek, and GPT-4 all use this architecture.

**Build on top:** Implement a small MoE transformer layer in PyTorch. Train a tiny MoE language model and compare perplexity and compute vs dense equivalent. Visualize which experts activate for different token types.

**Stack:** `Python` `PyTorch` `Matplotlib` `Weights & Biases` `GPU`  
**Signal:** Architecture research — frontier-level understanding

---

### R-12 · Sparse Priming Representations (SPR) for LLM Memory Compression
🟣 Research · *David Shapiro · 2023 · GitHub: daveshap/SparsePrimingRepresentations*

SPR compresses large amounts of information into dense, semantically rich bullet points that efficiently prime LLMs. Effectively a lossy compression format designed specifically for LLM context windows.

**Build on top:** Build a long-term memory system for AI agents using SPR compression. Compress past conversations into SPR format, store in a vector DB, retrieve and reconstruct for new sessions. Measure token savings vs retrieval quality.

**Stack:** `Python` `Claude API` `Pinecone` `Custom compression` `FastAPI`  
**Signal:** Memory architecture + context engineering depth

---

## 05 — Industry Verticals

> Your prior industry experience is your biggest unfair advantage. An AI engineer who actually understands the domain problem is worth 3x a generalist. Pick one vertical and go deep.

---

### V-01 · Automotive: AI Parts Catalog + Fitment Intelligence
🔵 Vertical · 🟡 High Value · ⏱ 6–8 weeks

Natural language search over parts catalogs. "What fits a 2019 Toyota Camry 2.5L?" Returns compatible parts with confidence, supplier options, and install instructions. Cross-reference multiple catalogs.

> Auto parts e-commerce is $70B. Fitment is the hardest search problem in the space. Domain knowledge here is a massive edge.

**Stack:** `Python` `Claude API` `pgvector` `ACES/PIES data` `FastAPI` `React`  
**Revenue:** $500–5k/mo per dealer · Your domain edge

---

### V-02 · E-Commerce: AI Amazon Listing Optimizer + PPC Analyzer
🔵 Vertical · 🟡 High Value · ⏱ 6–8 weeks

Input ASIN or product. Scrape current listing, competitor listings, search terms. Generate optimized title, bullets, A+ content. Analyze PPC bids vs search volume. Track listing score over time.

> Amazon seller tools market is $1B+. Sellers pay $200–2k/mo for optimization tools.

**Stack:** `Python` `Claude API` `Jungle Scout API` `SP-API` `FastAPI` `React`  
**Revenue:** $99–499/mo per seller account

---

### V-03 · Enigmax HiggsField MVP: AI Research OS
🔴 Vertical · 🟡 High Value · ⏱ 10–16 weeks

Vertical AI OS for researchers and knowledge workers. Ingest papers, notes, books. Ask cross-document questions. Auto-build knowledge graph of concepts and relationships. Track open questions. Export to reports.

> Build it as a real product, not a demo. The first version with 10 paying researchers will teach you more than 6 months of planning.

**Stack:** `Python` `Claude API` `Neo4j` `Weaviate` `FastAPI` `React` `RAGAS`  
**Revenue:** $49–199/mo · Your actual startup

---

### V-04 · Manufacturing: QA Defect Detection + Root Cause AI
🔵 Vertical · 🟡 High Value · ⏱ 8–10 weeks

Vision model flags defects in product images. LLM analyzes defect patterns against production parameters to suggest root causes. Tracks defect rate trends. Generates shift reports automatically.

> Manufacturing quality AI is massively underserved outside Tier 1 auto. A single 10% defect reduction for a mid-size plant is worth millions.

**Stack:** `Python` `Claude Vision` `YOLOv8` `FastAPI` `Postgres` `Grafana`  
**Revenue:** $2k–10k/mo per production line

---

## 🧭 How to Use This Guide

1. **Start at your level.** If you've never deployed an LLM app, do P-01 or P-02 first.
2. **Pick monetizable projects first.** Revenue validates the skill faster than portfolio views.
3. **Do one research reimplementation.** Even one R-0x project puts you in a different tier of candidates.
4. **Leverage your domain.** If you have industry experience, a V-0x project is your highest-leverage move.
5. **Eval everything.** The projects without evals are incomplete. Add RAGAS, custom scorers, or A/B tests.
6. **Ship before perfect.** A deployed project with rough edges > a perfect project on localhost.

---

## 🔧 Common Tech Stack Reference

| Category | Tools |
|----------|-------|
| LLM APIs | Claude API, OpenAI, Gemini, Hugging Face |
| Vector DBs | Pinecone, ChromaDB, Weaviate, pgvector, FAISS |
| Agent Frameworks | LangChain, LangGraph, Temporal |
| Eval | RAGAS, MLflow, Weights & Biases, BLEURT |
| Backend | FastAPI, Flask, Docker, Redis, Postgres |
| Frontend | React, Streamlit, Plotly Dash |
| Fine-tuning | QLoRA, unsloth, TRL, vLLM |
| Audio/Voice | Whisper, ElevenLabs, pyannote, Pipecat |
| Observability | OpenTelemetry, ClickHouse, Prometheus, Grafana |

---

> *Build things that already have buyers. Ship before perfect. Eval everything.*
