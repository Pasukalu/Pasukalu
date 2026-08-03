<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&duration=2500&pause=500&color=58A6FF&center=true&vCenter=true&width=600&lines=AI+Engineer+%7C+AI+%E5%B7%A5%E7%A8%8B%E5%B8%88;RAG+%C2%B7+Agents+%C2%B7+LLM+Eval+%C2%B7+Fine-tuning;Building+production-grade+AI+systems;8+projects+%C2%B7+757+tests+passed" alt="Typing SVG" />
</p>

---

## ð Hi, I'm Pasukalu

**AI Engineer** based in Guangdong, China. I build production-grade AI systems â from RAG pipelines and multi-agent orchestration to LLM evaluation infrastructure and model fine-tuning. Every project ships with CI/CD, comprehensive tests, and evaluation gates.

Before the code, I spent 5 years as a content creator and community operator â 18k+ followers, 8k-member communities, 100k+ plays, and features by The Paper (æ¾æ¹æ°é») and Luo Tianyi official. That product sense carries into everything I build.

```yaml
role: "AI Engineer"
focus: ["RAG", "Multi-Agent Systems", "LLM Evaluation", "PEFT Fine-tuning", "MCP Protocol"]
languages: ["Python", "TypeScript", "Go"]
frameworks: ["FastAPI", "LangGraph", "PyTorch", "Pydantic", "Docker"]
testing: "757 tests across 8 projects"
soft_skills: ["Product Sense", "Community Growth", "Content Strategy", "Business Japanese"]
philosophy: "If it doesn't have evals and CI gates, it's not production-ready."
```

---

## ð AI Engineering Portfolio

> 8 production-grade projects Â· 757 tests Â· all CI-green Â· all open-source

### 1. Production-Grade RAG QA System

<a href="https://github.com/Pasukalu/rag-qa-system/actions/workflows/ci.yml">
  <img src="https://github.com/Pasukalu/rag-qa-system/actions/workflows/ci.yml/badge.svg" alt="CI" />
</a>
<img src="https://img.shields.io/badge/tests-10%20passed-brightgreen" alt="Tests" />
<img src="https://img.shields.io/badge/recall%405-1.0-blue" alt="Recall" />
<img src="https://img.shields.io/badge/hallucination-0%25-success" alt="Hallucination" />

Two-stage retrieval pipeline: BM25 + dense embeddings fused via RRF â cross-encoder reranking. CI-gated evaluation (recall@k, MRR, faithfulness) auto-blocks PRs on quality regression. Dockerized with token-level cost tracking ($0.0003/query).

`Python` `FastAPI` `sentence-transformers` `rank-bm25` `Docker`

â [**View Repository**](https://github.com/Pasukalu/rag-qa-system)

---

### 2. Model Serving API with A/B Testing

<a href="https://github.com/Pasukalu/model-serving-api/actions/workflows/ci.yml">
  <img src="https://github.com/Pasukalu/model-serving-api/actions/workflows/ci.yml/badge.svg" alt="CI" />
</a>
<img src="https://img.shields.io/badge/tests-25%20passed-brightgreen" alt="Tests" />
<img src="https://img.shields.io/badge/endpoints-8-blue" alt="Endpoints" />

Production ML inference API with model versioning, hash-based A/B router for deterministic traffic splitting, and sliding-window metrics (p50/p95 latency, error rate). Runtime config hot-reload â no restart needed.

`Python` `FastAPI` `sentence-transformers` `scikit-learn` `Docker`

â [**View Repository**](https://github.com/Pasukalu/model-serving-api)

---

### 3. Multi-Agent Research System (LangGraph)

<a href="https://github.com/Pasukalu/multi-agent-system/actions/workflows/ci.yml">
  <img src="https://github.com/Pasukalu/multi-agent-system/actions/workflows/ci.yml/badge.svg" alt="CI" />
</a>
<img src="https://img.shields.io/badge/tests-67%20passed-brightgreen" alt="Tests" />
<img src="https://img.shields.io/badge/tools-6-blue" alt="Tools" />
<img src="https://img.shields.io/badge/guardrails-3-success" alt="Guardrails" />

4-node LangGraph pipeline (planner â executor â reviewer â reporter) with conditional routing, human-in-the-loop approval via checkpoint interrupt, and 3 guardrails (cost cap, exponential backoff retry, AST-validated safety checks).

`Python` `LangGraph` `FastAPI` `Pydantic` `Docker`

â [**View Repository**](https://github.com/Pasukalu/multi-agent-system)

---

### 4. LLM Evaluation Suite

<a href="https://github.com/Pasukalu/llm-eval-suite/actions/workflows/ci.yml">
  <img src="https://github.com/Pasukalu/llm-eval-suite/actions/workflows/ci.yml/badge.svg" alt="CI" />
</a>
<img src="https://img.shields.io/badge/tests-84%20passed-brightgreen" alt="Tests" />
<img src="https://img.shields.io/badge/golden%20set-200-blue" alt="Golden Set" />
<img src="https://img.shields.io/badge/CI%20gates-4-success" alt="CI Gates" />

200-case golden set across 6 categories with 10 metrics per case: lexical (EM, Token F1, ROUGE-L), RAGAS-inspired (faithfulness, answer relevance, context precision), and LLM-as-judge (correctness Ã completeness Ã clarity). 4 CI quality gates auto-block PRs.

`Python` `FastAPI` `Pydantic` `Docker`

â [**View Repository**](https://github.com/Pasukalu/llm-eval-suite)

---

### 5. LoRA Fine-tuning with Base-vs-Tuned Evaluation

<a href="https://github.com/Pasukalu/lora-finetuning/actions/workflows/ci.yml">
  <img src="https://github.com/Pasukalu/lora-finetuning/actions/workflows/ci.yml/badge.svg" alt="CI" />
</a>
<img src="https://img.shields.io/badge/tests-89%20passed-brightgreen" alt="Tests" />
<img src="https://img.shields.io/badge/improvement-0.12%E2%86%920.80-success" alt="Improvement" />

Dual-mode LoRA/QLoRA fine-tuning pipeline (stub for CI + real with PEFT/transformers). Base-vs-tuned comparison with multi-metric scoring (exact match, Token F1, ROUGE-L) and automatic deployment recommendation. 170 training / 50 evaluation samples across 4 task types.

`Python` `PEFT` `Transformers` `FastAPI` `Docker`

â [**View Repository**](https://github.com/Pasukalu/lora-finetuning)

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

â [**View Repository**](https://github.com/Pasukalu/mcp-agent-system)

---

### 7. nanoGPT + BPE Tokenizer (From Scratch)

<a href="https://github.com/Pasukalu/nanogpt-bpe/actions/workflows/ci.yml">
  <img src="https://github.com/Pasukalu/nanogpt-bpe/actions/workflows/ci.yml/badge.svg" alt="CI" />
</a>
<img src="https://img.shields.io/badge/tests-166%20passed-brightgreen" alt="Tests" />
<img src="https://img.shields.io/badge/compression-2.75x-blue" alt="Compression" />
<img src="https://img.shields.io/badge/params-10M-blueviolet" alt="Params" />

Byte-level BPE tokenizer implemented from scratch in pure Python (same algorithm as GPT-2/GPT-4). Complete Transformer architecture with documented math: LayerNorm, multi-head causal self-attention (softmax(QK^T/âd_k)V), GELU, pre-norm residual blocks. Dual-mode training (stub: bigram / real: torch).

`Python` `FastAPI` `Pydantic` `Docker`

â [**View Repository**](https://github.com/Pasukalu/nanogpt-bpe)

---

### 8. VN-Lite â Web Visual Novel Engine

<a href="https://github.com/Pasukalu/vn-lite/actions/workflows/ci.yml">
  <img src="https://github.com/Pasukalu/vn-lite/actions/workflows/ci.yml/badge.svg" alt="CI" />
</a>
<a href="https://github.com/Pasukalu/vn-lite/actions/workflows/deploy.yml">
  <img src="https://github.com/Pasukalu/vn-lite/actions/workflows/deploy.yml/badge.svg" alt="Deploy" />
</a>
<img src="https://img.shields.io/badge/tests-323%20passed-brightgreen" alt="Tests" />
<img src="https://img.shields.io/badge/bundle-285KB-blue" alt="Bundle" />
<img src="https://img.shields.io/badge/demo-live-success" alt="Demo" />

Lightweight web-based visual novel engine + editor with a Ren'Py-inspired text DSL. Custom script language with variables, conditionals, loops, subroutines, expression engine, and text interpolation. Full game systems: character sprites, NVL mode, particles, inventory, timed choices, achievements, CG gallery, i18n. Zero external asset dependencies â pure SVG + CSS + Web Audio API.

[**Live Demo**](https://pasukalu.github.io/vn-lite/) Â· `TypeScript` `React 18` `Vite` `CodeMirror 6` `Vitest` `Playwright`

â [**View Repository**](https://github.com/Pasukalu/vn-lite)

---

## ð Portfolio at a Glance

```
âââââââââââââââââââââââââââââââââââââââââââââââââââââââââââââââââââââââ
â  Project              Tests   Lines    Core Capability              â
âââââââââââââââââââââââââââââââââââââââââââââââââââââââââââââââââââââââ¤
â  rag-qa-system           10   ~1,300   AI/ML Pipeline Design        â
â  model-serving-api       25   ~1,800   ML Serving Engineering       â
â  multi-agent-system      67   ~2,800   Agent System Design          â
â  llm-eval-suite          84   ~2,800   Evaluation Engineering       â
â  lora-finetuning         89   ~2,900   Model Fine-tuning            â
â  mcp-agent-system        93   ~3,470   Protocol + Tool Orchestrationâ
â  nanogpt-bpe            166   ~4,350   LLM Fundamentals             â
â  vn-lite                323  ~13,400   Full-Stack Web Engine        â
âââââââââââââââââââââââââââââââââââââââââââââââââââââââââââââââââââââââ¤
â  TOTAL                 757  ~32,820   AI Engineering Full Stack     â
âââââââââââââââââââââââââââââââââââââââââââââââââââââââââââââââââââââââ
```

**Coverage**: RAG â Model Serving â Multi-Agent â LLM Evaluation â Fine-tuning â MCP Protocol â LLM Fundamentals â Full-Stack Web Engine

---

## ð± The Path Here: Content â Games â AI

I didn't start with code â I started by making things people actually watch, read, and play:

- **Fan visual novel producer** â led *æç¦ç¹äºä»¶ç°¿*, a Genshin-themed fan visual novel built on Unity/Naninovel: 18,000+ followers, 8,000+ member fan group, 5.59M+ Weibo topic reads, 4,500+ interactions.
- **Video creator & producer** â *åç©å¾å¿* science series (96k+ views, 11k fans, covered by The Paper), plus a 100k+ play VOCALOID MV that ranked #3 on Bilibili's Weekly VOCALOID Chinese Chart and #182 on the 2020 annual chart.
- **Community builder** â ran a high-retention 8,000-person fan community and delivered 200+ content projects end-to-end, with features by The Paper and Luo Tianyi official.

That first project is exactly why [vn-lite](https://github.com/Pasukalu/vn-lite) exists: I managed a visual novel built on someone else's engine, then wrote my own from scratch â script language, editor, and all.

---

## ðï¸ Other Work

**AI-powered products**

- **[BlissShop](https://blissshop.life)** â Fashion e-commerce brand for the confident Asian woman
- **[blissflow-short-copy](https://github.com/Pasukalu/blissflow-short-copy)** â AI-powered copy generator (short copy, long copy, video scripts) in Traditional Chinese, English & Japanese

**Creative & content track (5 years, before AI)**

- **æç¦ç¹äºä»¶ç°¿** â Genshin fan visual novel Â· producer & music lead Â· 18k+ followers, 8k+ community, 5.59M+ Weibo reads
- **ãåç©å¾å¿ã** â science video series Â· creator & producer Â· 96k+ views, 11k fans, featured by The Paper
- **ãéå¸¸è¡ä¸ºååãMV** â VOCALOID MV Â· producer Â· 100k+ plays Â· Bilibili Chinese Chart #406 3rd, 2020 annual #182
- **ãé»åºåè¡Dåºå£ã** â graduation song Â· producer Â· recommended by Luo Tianyi official
- **Event seat-query H5** â full-stack build & ops on Tencent Cloud CDN (1ms pings in some regions, zero downtime)

---

## ð GitHub Stats

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

## ð« Let's Connect

I'm open to AI Engineer opportunities. If you're hiring or want to collaborate:

- ð§ mrpascalpa@icloud.com
- ð¼ [Projects & Details](https://github.com/Pasukalu?tab=repositories)

---

<p align="center">
  <i>From bytes to tokens to embeddings to attention to generation â and the full-stack engines that put them in production. Built from scratch, tested end-to-end.</i>
</p>
