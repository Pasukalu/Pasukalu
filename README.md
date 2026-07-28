<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&duration=2500&pause=500&color=58A6FF&center=true&vCenter=true&width=600&lines=AI+Engineer+%7C+AI+%E5%B7%A5%E7%A8%8B%E5%B8%88;RAG+%C2%B7+Agents+%C2%B7+LLM+Eval+%C2%B7+Fine-tuning;Building+production-grade+AI+systems;8+projects+%C2%B7+757+tests+passed" alt="Typing SVG" />
</p>

---

## 👋 Hi, I'm Pasukalu

**AI Engineer** based in Guangdong, China. I build production-grade AI systems — from RAG pipelines and multi-agent orchestration to LLM evaluation infrastructure and model fine-tuning. Every project ships with CI/CD, comprehensive tests, and evaluation gates.

```yaml
role: "AI Engineer"
focus: ["RAG", "Multi-Agent Systems", "LLM Evaluation", "PEFT Fine-tuning", "MCP Protocol"]
languages: ["Python", "TypeScript", "Go"]
frameworks: ["FastAPI", "LangGraph", "PyTorch", "Pydantic", "Docker"]
testing: "757 tests across 8 projects"
philosophy: "If it doesn't have evals and CI gates, it's not production-ready."
```

---

## 🚀 AI Engineering Portfolio

> 8 production-grade projects · 757 tests · all CI-green · all open-source

### 1. Production-Grade RAG QA System

<a href="https://github.com/Pasukalu/rag-qa-system/actions/workflows/ci.yml">
  <img src="https://github.com/Pasukalu/rag-qa-system/actions/workflows/ci.yml/badge.svg" alt="CI" />
</a>
<img src="https://img.shields.io/badge/tests-10%20passed-brightgreen" alt="Tests" />
<img src="https://img.shields.io/badge/recall%405-1.0-blue" alt="Recall" />
<img src="https://img.shields.io/badge/hallucination-0%25-success" alt="Hallucination" />

Two-stage retrieval pipeline: BM25 + dense embeddings fused via RRF → cross-encoder reranking. CI-gated evaluation (recall@k, MRR, faithfulness) auto-blocks PRs on quality regression. Dockerized with token-level cost tracking ($0.0003/query).

`Python` `FastAPI` `sentence-transformers` `rank-bm25` `Docker`

→ [**View Repository**](https://github.com/Pasukalu/rag-qa-system)

---

### 2. Model Serving API with A/B Testing

<a href="https://github.com/Pasukalu/model-serving-api/actions/workflows/ci.yml">
  <img src="https://github.com/Pasukalu/model-serving-api/actions/workflows/ci.yml/badge.svg" alt="CI" />
</a>
<img src="https://img.shields.io/badge/tests-25%20passed-brightgreen" alt="Tests" />
<img src="https://img.shields.io/badge/endpoints-8-blue" alt="Endpoints" />

Production ML inference API with model versioning, hash-based A/B router for deterministic traffic splitting, and sliding-window metrics (p50/p95 latency, error rate). Runtime config hot-reload — no restart needed.

`Python` `FastAPI` `sentence-transformers` `scikit-learn` `Docker`

→ [**View Repository**](https://github.com/Pasukalu/model-serving-api)

---

### 3. Multi-Agent Research System (LangGraph)

<a href="https://github.com/Pasukalu/multi-agent-system/actions/workflows/ci.yml">
  <img src="https://github.com/Pasukalu/multi-agent-system/actions/workflows/ci.yml/badge.svg" alt="CI" />
</a>
<img src="https://img.shields.io/badge/tests-67%20passed-brightgreen" alt="Tests" />
<img src="https://img.shields.io/badge/tools-6-blue" alt="Tools" />
<img src="https://img.shields.io/badge/guardrails-3-success" alt="Guardrails" />

4-node LangGraph pipeline (planner → executor → reviewer → reporter) with conditional routing, human-in-the-loop approval via checkpoint interrupt, and 3 guardrails (cost cap, exponential backoff retry, AST-validated safety checks).

`Python` `LangGraph` `FastAPI` `Pydantic` `Docker`

→ [**View Repository**](https://github.com/Pasukalu/multi-agent-system)

---

### 4. LLM Evaluation Suite

<a href="https://github.com/Pasukalu/llm-eval-suite/actions/workflows/ci.yml">
  <img src="https://github.com/Pasukalu/llm-eval-suite/actions/workflows/ci.yml/badge.svg" alt="CI" />
</a>
<img src="https://img.shields.io/badge/tests-84%20passed-brightgreen" alt="Tests" />
<img src="https://img.shields.io/badge/golden%20set-200-blue" alt="Golden Set" />
<img src="https://img.shields.io/badge/CI%20gates-4-success" alt="CI Gates" />

200-case golden set across 6 categories with 10 metrics per case: lexical (EM, Token F1, ROUGE-L), RAGAS-inspired (faithfulness, answer relevance, context precision), and LLM-as-judge (correctness × completeness × clarity). 4 CI quality gates auto-block PRs.

`Python` `FastAPI` `Pydantic` `Docker`

→ [**View Repository**](https://github.com/Pasukalu/llm-eval-suite)

---

### 5. LoRA Fine-tuning with Base-vs-Tuned Evaluation

<a href="https://github.com/Pasukalu/lora-finetuning/actions/workflows/ci.yml">
  <img src="https://github.com/Pasukalu/lora-finetuning/actions/workflows/ci.yml/badge.svg" alt="CI" />
</a>
<img src="https://img.shields.io/badge/tests-89%20passed-brightgreen" alt="Tests" />
<img src="https://img.shields.io/badge/improvement-0.12%E2%86%920.80-success" alt="Improvement" />

Dual-mode LoRA/QLoRA fine-tuning pipeline (stub for CI + real with PEFT/transformers). Base-vs-tuned comparison with multi-metric scoring (exact match, Token F1, ROUGE-L) and automatic deployment recommendation. 170 training / 50 evaluation samples across 4 task types.

`Python` `PEFT` `Transformers` `FastAPI` `Docker`

→ [**View Repository**](https://github.com/Pasukalu/lora-finetuning)

---

### 6. MCP Server + Agent Tool Orchestration

<a href="https://github.com/Pasukalu/mcp-agent-system/actions/workflows/ci.yml">
  <img src="https://github.com/Pasukalu/mcp-agent-system/actions/workflows/ci.yml/badge.svg" alt="CI" />
</a>
<img src="https://img.shields.io/badge/tests-93%20passed-brightgreen" alt="Tests" />
<img src="https://img.shields.io/badge/tools-6-blue" alt="Tools" />
<img src="https://img.shields.io/badge/safety-AST%20validated-success" alt="Safety" />

Model Context Protocol server with 3 primitives (Tools/Resources/Prompts) and 6 sandboxed tools: AST-validated code executor, virtual filesystem manager, simulated web searcher, CSV data analyzer, git helper, and math calculator. Agent orchestration with plan-execute-verify loop.

`Python` `FastAPI` `Pydantic` `Docker`

→ [**View Repository**](https://github.com/Pasukalu/mcp-agent-system)

---

### 7. nanoGPT + BPE Tokenizer (From Scratch)

<a href="https://github.com/Pasukalu/nanogpt-bpe/actions/workflows/ci.yml">
  <img src="https://github.com/Pasukalu/nanogpt-bpe/actions/workflows/ci.yml/badge.svg" alt="CI" />
</a>
<img src="https://img.shields.io/badge/tests-166%20passed-brightgreen" alt="Tests" />
<img src="https://img.shields.io/badge/compression-2.75x-blue" alt="Compression" />
<img src="https://img.shields.io/badge/params-10M-blueviolet" alt="Params" />

Byte-level BPE tokenizer implemented from scratch in pure Python (same algorithm as GPT-2/GPT-4). Complete Transformer architecture with documented math: LayerNorm, multi-head causal self-attention (softmax(QK^T/√d_k)V), GELU, pre-norm residual blocks. Dual-mode training (stub: bigram / real: torch).

`Python` `FastAPI` `Pydantic` `Docker`

→ [**View Repository**](https://github.com/Pasukalu/nanogpt-bpe)

---

### 8. VN-Lite — Web Visual Novel Engine

<a href="https://github.com/Pasukalu/vn-lite/actions/workflows/ci.yml">
  <img src="https://github.com/Pasukalu/vn-lite/actions/workflows/ci.yml/badge.svg" alt="CI" />
</a>
<a href="https://github.com/Pasukalu/vn-lite/actions/workflows/deploy.yml">
  <img src="https://github.com/Pasukalu/vn-lite/actions/workflows/deploy.yml/badge.svg" alt="Deploy" />
</a>
<img src="https://img.shields.io/badge/tests-323%20passed-brightgreen" alt="Tests" />
<img src="https://img.shields.io/badge/bundle-285KB-blue" alt="Bundle" />
<img src="https://img.shields.io/badge/demo-live-success" alt="Demo" />

Lightweight web-based visual novel engine + editor with a Ren'Py-inspired text DSL. Custom script language with variables, conditionals, loops, subroutines, expression engine, and text interpolation. Full game systems: character sprites, NVL mode, particles, inventory, timed choices, achievements, CG gallery, i18n. Zero external asset dependencies — pure SVG + CSS + Web Audio API.

[**Live Demo**](https://pasukalu.github.io/vn-lite/) · `TypeScript` `React 18` `Vite` `CodeMirror 6` `Vitest` `Playwright`

→ [**View Repository**](https://github.com/Pasukalu/vn-lite)

---

## 📊 Portfolio at a Glance

```
┌─────────────────────────────────────────────────────────────────────┐
│  Project              Tests   Lines    Core Capability              │
├─────────────────────────────────────────────────────────────────────┤
│  rag-qa-system           10   ~1,300   AI/ML Pipeline Design        │
│  model-serving-api       25   ~1,800   ML Serving Engineering       │
│  multi-agent-system      67   ~2,800   Agent System Design          │
│  llm-eval-suite          84   ~2,800   Evaluation Engineering       │
│  lora-finetuning         89   ~2,900   Model Fine-tuning            │
│  mcp-agent-system        93   ~3,470   Protocol + Tool Orchestration│
│  nanogpt-bpe            166   ~4,350   LLM Fundamentals             │
│  vn-lite                323  ~13,400   Full-Stack Web Engine        │
├─────────────────────────────────────────────────────────────────────┤
│  TOTAL                 757  ~32,820   AI Engineering Full Stack     │
└─────────────────────────────────────────────────────────────────────┘
```

**Coverage**: RAG → Model Serving → Multi-Agent → LLM Evaluation → Fine-tuning → MCP Protocol → LLM Fundamentals → Full-Stack Web Engine

---

## 🛍️ Other Work

Before focusing on AI engineering, I built:

- **[BlissShop](https://blissshop.life)** — Fashion e-commerce brand for the confident Asian woman
- **[blissflow-short-copy](https://github.com/Pasukalu/blissflow-short-copy)** — AI-powered copy generator (short copy, long copy, video scripts) in Traditional Chinese, English & Japanese

---

## 📈 GitHub Stats

<p align="center">
  <img src="https://img.shields.io/badge/public%20repos-31-blue?style=for-the-badge&logo=github" alt="Public Repos" />
  <img src="https://img.shields.io/badge/languages-Python%20%7C%20TypeScript%20%7C%20Go-blueviolet?style=for-the-badge&logo=probot" alt="Languages" />
  <img src="https://img.shields.io/badge/tests-757%20passed-brightgreen?style=for-the-badge&logo=pytest" alt="Tests" />
  <img src="https://img.shields.io/badge/CI%20pipelines-9%20all%20green-success?style=for-the-badge&logo=github-actions" alt="CI Pipelines" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Pasukalu&theme=github-dark-blue&hide_border=true" alt="GitHub Streak" />
</p>

---

## 📫 Let's Connect

I'm open to AI Engineer opportunities. If you're hiring or want to collaborate:

- 📧 Reach out via GitHub
- 💼 [Resume & Project Details](https://github.com/Pasukalu?tab=repositories)

---

<p align="center">
  <i>From bytes to tokens to embeddings to attention to generation — and the full-stack engines that put them in production. Built from scratch, tested end-to-end.</i>
</p>
