<div align="center">

# Pasukalu · 帕苏卡露

**AI Application Engineering · RAG · Agents · Evaluation**

把 AI 能力做成可运行、可检查、好使用的产品。

Building AI applications with clear evidence, useful interfaces, and reproducible checks.

[Featured project](https://github.com/Pasukalu/mochi-reader) · [All repositories](https://github.com/Pasukalu?tab=repositories) · [VN-Lite demo](https://pasukalu.github.io/vn-lite/) · [Email](mailto:mrpascalpa@icloud.com)

</div>

## About

I focus on **AI application engineering**: connecting retrieval, models, tools, evaluation, and user-facing products.

- **Current role:** HK AI Engineer (WFH)
- **Based in:** Guangdong, China
- **Open to:** AI Application Engineer / AI Engineer opportunities, developer tools, and open-source collaboration
- **Languages:** Python · TypeScript · JavaScript · Go
- **Tools across my projects:** FastAPI · Pydantic · SQLite · LangGraph · PyTorch · Docker · GitHub Actions

My background also includes fan-game production, science communication, music production, and community operations. Those experiences shape how I explain technical ideas and design for real users.

## Featured: Mochi Reader · 糯米

<a href="https://github.com/Pasukalu/mochi-reader"><img align="right" src="https://raw.githubusercontent.com/Pasukalu/mochi-reader/main/web/whale.png" width="130" alt="Mochi Reader whale-girl companion"></a>

**鲸鱼娘陪你读技术文档：原文引用问答、学习卡与自测。**

[Mochi Reader](https://github.com/Pasukalu/mochi-reader) combines a local reading workspace with a Chrome MV3 side panel. Import a page or selection, ask a question, inspect its sources, and turn the material into study cards and quizzes.

- **Model settings in the UI:** configure a DeepSeek / compatible API key, base URL, and model; saved changes apply without a restart.
- **Traceable retrieval:** English tokens and Chinese bigrams, a BM25 lexical baseline, and stable source-fragment IDs.
- **A complete reading loop:** cited Q&A → study cards → comprehension checks → Markdown export.
- **Clear operating modes:** an explicitly labeled extractive demo without a key, plus a live-provider adapter.

**Stack:** Python · FastAPI · SQLite · Vanilla JavaScript · SSE · Chrome MV3

Citation checks validate source references; they do not prove factual correctness. Local automated checks use mocks, and no live-model quality result is claimed.

[Read the project →](https://github.com/Pasukalu/mochi-reader) · [Architecture](https://github.com/Pasukalu/mochi-reader/blob/main/docs/architecture.md) · [Character notes](https://github.com/Pasukalu/mochi-reader/blob/main/docs/characters.md)

<br clear="right">

## More AI engineering work

| Project | Focus |
| --- | --- |
| [RAG QA System](https://github.com/Pasukalu/rag-qa-system) | BM25 + dense retrieval, RRF fusion, cross-encoder reranking, citations, and retrieval evaluation. |
| [Multi-Agent Research System](https://github.com/Pasukalu/multi-agent-system) | LangGraph planning, execution, review, human approval, checkpoints, and retries. |
| [LLM Evaluation Suite](https://github.com/Pasukalu/llm-eval-suite) | Evaluation datasets, answer metrics, cost/latency reports, and configurable CI gates. |
| [MCP Agent System](https://github.com/Pasukalu/mcp-agent-system) | MCP tools and resources, plan–execute–verify orchestration, and offline / live modes. |
| [Model Serving API](https://github.com/Pasukalu/model-serving-api) | Versioned inference, deterministic A/B routing, lazy loading, and latency/error metrics. |

## Foundations & creative tools

| Project | Focus |
| --- | --- |
| [nanoGPT + BPE](https://github.com/Pasukalu/nanogpt-bpe) | Byte-level BPE and decoder-only Transformer architecture, with an offline demo mode. |
| [LoRA Fine-tuning](https://github.com/Pasukalu/lora-finetuning) | LoRA / QLoRA workflows, stub and real modes, and base-versus-tuned comparisons. |
| [Claude Design System Prompt](https://github.com/Pasukalu/claude-design-system-prompt) | A system-prompt and procedural-skill library for interface design and accessibility. |
| [VN-Lite](https://github.com/Pasukalu/vn-lite) | A browser visual-novel engine and editor with a text DSL, branching stories, saves, and i18n. **[Try the demo →](https://pasukalu.github.io/vn-lite/)** |

## How I approach projects

- Keep the default path runnable, including offline or mock modes where useful.
- Make sources, errors, and operating limits visible to the user.
- Evaluate a specific claim before reporting an improvement; separate simulated results from live-model evidence.
- Ship the interface, API, tests, documentation, and a clear next experiment together.

## Let’s connect

I’m looking for **AI application engineering opportunities** and collaborators building useful LLM applications, developer tools, and creative technology.

- **Email:** [mrpascalpa@icloud.com](mailto:mrpascalpa@icloud.com)
- **Projects:** [github.com/Pasukalu](https://github.com/Pasukalu?tab=repositories)
